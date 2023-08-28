## Overview
This is a simple script for installing Asterisk 20 on Ubuntu 22.

## How install Asterisk 20

    # become a root
    sudo -i
    # interactively run the shell script (helps menuselect work properly)
    bash <(wget -q -O - https://raw.githubusercontent.com/hserge/asterisk-setup/main/asterisk-setup.txt)

## How install FreePBX 16

    # become a root
    sudo -i
    # interactively run the shell script
    bash <(wget -q -O - https://raw.githubusercontent.com/hserge/asterisk-setup/main/freepbx-setup.txt)

## Issues
- During the Asterisk config reload there are a few errors and warnings which still must be fixed manually by fine-tuning the config files. Too much work programmatically add/replace/delete config file directives in the shell.
