# Fork
This is a fork of yakov's version-hash-saver, changed to make a text file with all discovered versions and changed to run every 5 minutes instead of every hour.

# version-hash-saver

#### Tracked endpoints:

When an update is detected, these endpoints get stored in this repository and get submitted to the Wayback Machine:

- https://clientsettings.roblox.com/v2/client-version/WindowsPlayer  
- https://clientsettings.roblox.com/v2/client-version/WindowsStudio64  
- https://clientsettings.roblox.com/v2/client-version/MacPlayer  
- https://clientsettings.roblox.com/v2/client-version/MacStudio  

For Studio builds only, an additional OTA endpoint is also archived:

- https://clientsettings.roblox.com/v2/ota-version/{platform}?version={major_version}

**Schedule:** Runs every 5 minutes via GitHub Actions.
