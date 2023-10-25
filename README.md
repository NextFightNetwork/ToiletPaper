# What is ToiletPaper?
Its Paper but without the end, nether, playerstats etc.
Its perfect for a minigame server.

## Changed
- Removed eula.txt
- Removed some commands

## TODO
- Unnecessary files 
- Option to disable all default commands for player
- Option for minigame server: not save player data and worlds also only load the main world & more
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
