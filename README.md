# Discord Auto-Updater Service

This repository contains the necessary files to set up a service that automatically updates Discord on system startup. This can help ensure that you always have the latest version of Discord ready to go without needing to manually check for updates.

## Usage

1. Run ```sudo systemctl daemon-reload ``` 

2. Copy the update_discord.sh to /opt/AutoUpdateDiscord/

3. Move the update_discord.service file to /etc/systemd/system

## Start the service

```bash
sudo systemctl enable update-discord.service
sudo systemctl start update-discord.service
```
