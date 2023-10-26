<div align="center">
    <a href="https://github.com/NextFightNetwork/ToiletPaper/releases"><img src="https://img.shields.io/github/v/tag/NextFightNetwork/ToiletPaper.svg" alt="Version"></a>  
</div>

# What is ToiletPaper?
Its a Paper fork without some "features".  
Perfect for a minigame server.

# What is different?
- Removed command aliases
- Removed eula.txt
- Reduced console logs
- Disabled timings
- Increased required permission level of some commands like /plugins or /version
- Improved tps command
- Added toiletpaper.yml
- Added auto downloaded plugins (which can be disabled in toiletpaper.yml)
  - AntiPopup

### Changed default options in some configs
> **Important**
> These will only be applied if configs like the server.properties or bukkit/spigot.yml file is generated by PaperToilet
  - Disabled end
  - Disabled nether
  - Disabled advancements
  - Disabled player stats saving
  - Disabled enforce secure player profile

## Config
`toiletpaper.yml`
```yml
Option:
  SaveWorlds: false
DownloadPlugins:
  1:
    NAME: AntiPopup-7.1.jar
    URL: https://nextfight.net/public/toiletpaper/plugins/AntiPopup-7.1.jar
```

## TODO
- Option to disable all default commands for player
- Option to not show player IP's in console
- Option to disable logs / minimal logs
- Less config files

You can still write plugins using the normal paper api but some features will be missing like the player statistics
