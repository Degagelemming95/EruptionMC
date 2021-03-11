<img src="https://static1.textcraft.net/data1/c/5/c58db7164ed4b18be6fb4ce8752e0ac2052eed47841126915be01660c7f312c5b313306343af85c1da39a3ee5e6b4b0d3255bfef95601890afd807093f3c16f489fe258e4a9f3351e7223657.png" width="800"/>

[![forthebadge made-with-java](http://ForTheBadge.com/images/badges/made-with-java.svg)](https://java.com/)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


EruptionMC is a fork of GeyserMC which is a bridge between Minecraft Bedrock and Java Edition. GeyserMC is an open collaboration software by CubeCraft Games. This project is a modfiied version of GeyserMC and it is not affiliated with CubeCraft Games nor any of their services. This build of Geyser is not supported by GeyserMC, all issues regarding GeyserMC should be made there. Special Thanks to GeyserMC for being a base software for us to modify. 

### Currently supporting Minecraft Bedrock v1.16.100 - v1.16.210 and Minecraft Java v1.16.4 - v1.16.5.

## What's Left to be Added/Fixed
- Structure Block UI
- Near-perfect movement (to the point where anticheat on large servers is unlikely to ban you)
- Resource pack conversion/CustomModelData
- Some Entity Flags 

## What can't be fixed
The following things can't be fixed because of Bedrock limitations. They might be fixable in the future, but not as of now.

- Custom heads in inventories
- Clickable links in chat
- Glowing effect
- Custom armor stand poses

## Compiling
1. Clone the repo to your computer
2. [Install Maven](https://maven.apache.org/install.html)
3. Navigate to the Geyser root directory and run `git submodule update --init --recursive`. This downloads all the needed submodules for Geyser and is a crucial step in this process.
4. Run `mvn clean install` and locate to the `target` folder.

## Contributing
This project is in its Alpha stage and contributions should be made to the main Geyser build at this time. Mian Geyser build can be found at https://geysermc.org

## Libraries Used:
- [NukkitX Bedrock Protocol Library](https://github.com/NukkitX/Protocol)
- [Steveice10's Java Protocol Library](https://github.com/Steveice10/MCProtocolLib)
- [TerminalConsoleAppender](https://github.com/Minecrell/TerminalConsoleAppender)
- [Simple Logging Facade for Java (slf4j)](https://github.com/qos-ch/slf4j)
