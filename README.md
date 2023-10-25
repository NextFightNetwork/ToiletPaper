<div align="center">
    <a href="https://github.com/NextFightNetwork/ToiletPaper/releases"><img src="https://img.shields.io/github/v/tag/NextFightNetwork/ToiletPaper.svg" alt="Version"></a>  
</div>

# What is ToiletPaper?
Its a Paper fork without some features.
Perfect for a minigame server.

## Changed
- Removed eula.txt
- Removed some commands
- Disabled nether & end by default
- Removed some warnings in console

## TODO
- Unnecessary files 
- Option to disable all default commands for player
- Option to not show player IP's in console
- Option to disable logs / minimal logs
- Less config files
- Remove advancements
- Remove chat report
- Remove rcon

## Installation

### Compile PaperToilet
- Clone this repo
- run `./gradlew applyPatches`
- run `./gradlew createReobfBundlerJar`
- The jar will be in build/libs

You can still write plugins using the normal paper api but some features will be missing like the player statistics
