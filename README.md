# Raspberry configurator

## Configure wi-fi access

### Install SSH Pass

    brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb

see [this gist](https://gist.github.com/arunoda/7790979) for details

### Configure WI-FI access 
    
    ansible-playbook --ask-vault-pass --inventory-file=inventory.yml wi-fi.yml

## Install AirPlay server

    ansible-playbook --ask-vault-pass --inventory-file=inventory.yml airplay.yml  

see [Shairport Sync](https://github.com/mikebrady/shairport-sync) for details.
