DigitalOcean SSH Key Updater
---

This script updates all droplets on DigitalOcean with all the keys stored in the SSH Keys section in the web interface.

For this to work you to have access using the current computers SSH key, then you can update it to include the whole list.

## Why?

I got really sick of updating all the ip addresses for all my servers, so I thought there must be a better way! Turns out there is.... this bash script

## Usage

When using for a once off you can use it like this

    export TOKEN="YOURAPITOKEN"
    ./update_droplet_keys.sh

If you want to use it regularly (e.g. from cron) then you can put the token in a file called .token in the script directory and simply run it
