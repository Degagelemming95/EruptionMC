<img src="https://i.imgur.com/PiXUpMQ.png" width="800"/>

[![forthebadge made-with-java](http://ForTheBadge.com/images/badges/made-with-java.svg)](https://java.com/)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


ErruptionMC is a fork of GeyserMC which is a bridge between Minecraft Bedrock and Java Edition. 

Modified version of GeyserMC which is an open collaboration software by CubeCraft Games.

Special thanks to the GeyserMC project for being a base software for us to modify!!

### Currently supporting Minecraft Bedrock v1.16.100 - v1.16.210 and Minecraft Java v1.16.4 - v1.16.5.

## What's Left to be Added/Fixed
- Lecterns
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
Any contributions are appreciated. Please feel free to reach out to us on [Discord](http://discord.geysermc.org/) if
you're interested in helping out with Geyser.

## Libraries Used:
- [NukkitX Bedrock Protocol Library](https://github.com/NukkitX/Protocol)
- [Steveice10's Java Protocol Library](https://github.com/Steveice10/MCProtocolLib)
- [TerminalConsoleAppender](https://github.com/Minecrell/TerminalConsoleAppender)
- [Simple Logging Facade for Java (slf4j)](https://github.com/qos-ch/slf4j)
