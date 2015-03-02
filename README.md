DigitalOcean SSH Key Updater
---

This script updates all droplets on DigitalOcean with all the keys stored in the SSH Keys section in the web interface.

For this to work you to have access using the current computers SSH key, then you can update it to include the whole list.

## USAGE

    export TOKEN="YOURAPITOKEN"
    ./update_droplet_keys.sh
