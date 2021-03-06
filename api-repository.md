# API repository

There are a lot of tools, libraries and frameworks for Bukkit-based plugin development.
This file lists an unexhaustive selection.

- [Frameworks](#Frameworks)
- [Utilities](#Utilities)
  - [Version Independent Code](#Version-Independent-Code)
  - [Dependency Management](#Dependency-Management)
  - [Bridges](#Bridges)
  - [Packets](#Packets)
- [Other Languages](#Other-Languages)
- [Commands](#Commands)
- [Libraries](#Libraries)
  - [NPCs](#NPCs)
  - [Maps](#Maps)
  - [GUIs](#GUIs)
  - [Scoreboards](#Scoreboards)
  - [Holograms](#Holograms)
  - [NBT](#NBT)
  - [Worlds](#Worlds)

## Frameworks

Full-blown frameworks that operate on top of Bukkit and define how you write your plugins.

- [kelp](https://github.com/PXAV/kelp) by [@PXAV](https://github.com/PXAV/)

  > kelp is an all-in-one framework that aims to avoid version-depended code.

  __Main features__:
  - Sidebar system
  - Inventory system
  - NPC system: 
  - Command system
  - Config system

## Utilities

Tools that help you with compatibility, interopability and workflow.

### Environment

- [MinecraftDev](https://github.com/minecraft-dev/MinecraftDev) by [@minecraft-dev](https://github.com/minecraft-dev)

  > An IntelliJ plugin that helps you with plugin projects, among others.

- [docker-minecraft-server](https://github.com/itzg/docker-minecraft-server) by [@itzg](https://github.com/itzg)

  > Dockerize minecraft servers by providing customizable images.

### Version Independent Code

- [XSeries](https://github.com/CryptoMorin/XSeries) by [@CryptoMorin](https://github.com/CryptoMorin)

  > XSeries provides abstraction for several version-depended classes.

  __Main features__:
  - potions, materials, sounds, particles, ...
  - blocks, entities, bioms
- [compatre](https://github.com/johnnyjayjay/compatre) by [@JohnnyJayJay](https://github.com/johnnyjayjay)

  > compatre replaces version-specific nms and craftbukkit types at runtime using bytecode manipulation.

  __Main features:__
  - Version compatibility with only a single annotation
  - Java agent/Custom class loader

### Dependency Management

- [pdm](https://github.com/knightzmc/pdm) by [@knightzmc](https://github.com/knightzmc)

  > pdm lets you add your external dependencies to the classpath without shading.
  
  __Main features:__
  - Declarative dependency notation
  - Reuse of shared dependencies (including transitive ones)
  - Plugin to integrate with Gradle
- [libby](https://github.com/Byteflux/libby) by [@Byteflux](https://github.com/Byteflux)

  > libby lets you add your external dependencies to the classpath without shading.
  
  __Main features:__
  - Dependency relocation
  
### Bridges

- [PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI) by [@extendedclip](https://github.com/extendedclip)

  > PlaceholderAPI provides a uniform way to share information with and use information from other plugins.
  
  __Main features:__
  - Developer API 
  - External expansions
- [Vault](https://github.com/milkbowl/Vault) by [@MilkBowl](https://github.com/milkbowl)

  > Vault provides bridge APIs for common plugin systems on Bukkit servers.
  
  __Main features:__
  - Economy API
  - Chat API
  - Permissions API
  
### Packets

- [ProtocolLib](https://github.com/dmulloy2/ProtocolLib) by [@aadnk](https://github.com/aadnk)/[@dmulloy2](https://github.com/dmulloy2)

  > ProtocolLib provides read and write access to the Minecraft server protocol in combination with Bukkit.
  
  __Main features:__
  - Packet interception
  - Obfuscation-free API

## Other Languages

Who says that you can only use Java to write plugins?

- [VisualBukkit](https://github.com/OfficialDonut/VisualBukkit) by [@OfficialDonut](https://github.com/OfficialDonut)

  > VisualBukkit is a visual programming language for Bukkit plugins.
  
- [Skript](https://github.com/SkriptLang/Skript) by [@bensku](https://github.com/bensku)

  > Skript is a domain specific language for Bukkit with the aim to enable non-programmers to be able to write their own plugins.

- [spiglin](https://github.com/johnnyjayjay/spiglin) by [@JohnnyJayJay](https://github.com/johnnyjayjay)

  > spiglin is a collection of extensions and utilities for plugins written in the [Kotlin](https://kotlinlang.org) programming language.
  
- [spigot-clj-template](https://github.com/johnnyjayjay/spigot-clj-template) by [@JohnnyJayJay](https://github.com/JohnnyJayJay)

  > spigot-clj-template is a [Leiningen](https://leiningen.org) template to write plugins using the [Clojure](https://clojure.org) programming language.

- [minecraft-python](https://github.com/Macuyiko/minecraft-python) by [@Macuyiko](https://github.com/Macuyiko)

  > minecraft-python is an interpreter system leveraging [Jython](https://www.jython.org/) to write Spigot plugins in Python.

## Commands

High-level alternatives and extensions for Bukkit's rusty command system. 
They all aim to reduce the boilerplate involved in writing commands the traditional way.

- [Annotation Command Framework](https://github.com/aikar/commands) by [@aikar](https://github.com/aikar/)
- [Matt's framework](https://github.com/ipsk/MattFramework) by [@ipsk](https://github.com/ipsk)
- [kaesk](https://github.com/DRSchlaubi/kaesk) by [@DRSchlaubi](https://github.com/DRSchlaubi)
- [simple-commands](https://github.com/Paul2708/simple-commands) by [@Paul2708](https://github.com/Paul2708)

## Libraries

Libraries are projects that focus on a specific aspect of plugins.

### NPCs

- [NPCLib](https://github.com/MinecraftLibraries/NPCLib) by [@JitseB](https://github.com/JitseB)

  > Library that allows developers to create NPCs with an easy-to-use API.
- [CitizensAPI](https://github.com/CitizensDev/CitizensAPI) by [@fullwall](https://github.com/fullwall)

  > API to create and manage NPCs using the [Citizens](https://github.com/CitizensDev/Citizens2) plugin

### Maps

- [spigot-maps](https://github.com/johnnyjayjay/spigot-maps) by [@JohnnyJayJay](https://github.com/johnnyjayjay)
  
  > Library to render custom images, gifs and text on Minecraft map items
  
  __Main features:__
  - Lots of customisation (how often to render, to whom to render, ...)
  - Tools to resize/crop/divide images and gifs to better fit maps
  - Persistence API
  
### GUIs

- [AnvilGUI](https://github.com/WesJD/AnvilGUI) by [@WesJD](https://github.com/WesJD/)

  > AnvilGUI provides an API to open an anvil inventory that reacts on renaming.

  __Main features__:
  - support of nearly every version
  - easy-to-use builder
  - set title, items, closing listener and completion listener

- [SmartInvs](https://github.com/MinusKube/SmartInvs) by [@MinusKube](https://github.com/MinusKube/)

  > SmartInvs provides an interface for creating inventories by setting clickable items.

  __Main features__:
  - Iterator for inventory slots
  - Page system
  - Util methods to fill an inventory's row/column/borders/...
  - Actions when player clicks on an item

  More features and examples can be found [here](https://minuskube.gitbook.io/smartinvs/).

### Scoreboards

- [Netherboard](https://github.com/MinusKube/Netherboard) by [@MinusKube](https://github.com/MinusKube/)

  > Netherboard provides a simple-to-use wrapper for scoreboards.

  __Main features__:
  - simple syntax for creation `BPlayerBoard board = Netherboard.instance().createBoard(player, scoreboard, "My Scoreboard");`
  - simple syntax for adding/removing scores: `board.set("Test Score", 5);`, `board.remove(5)`

- [MultiLineAPI](https://github.com/iso2013/MultiLineAPI) by [@iso2013](https://github.com/iso2013/)

  > This API adds custom lines of text below a players name.
  
### Holograms

- [HolographicDisplays](https://github.com/filoghost/HolographicDisplays) by [@filoghost](https://github.com/filoghost)

  > Plugin and API to create holograms.
  
### NBT

- [Item-NBT-API](https://github.com/tr7zw/Item-NBT-API) by [@tr7zw](https://github.com/tr7zw)

  > NMS-free NBT api with yaml, json, SQL and Redis serialization.
  
### Worlds

- [WorldGeneratorAPI](https://github.com/rutgerkok/WorldGeneratorApi) by [@rutgerkok](https://github.com/rutgerkok)

  > API to create custom world generators easily.
  
- [WorldEdit](https://github.com/EngineHub/WorldEdit) by [@sk89q](https://github.com/sk89q)
  
  > Plugin and API to manipulate Minecraft worlds.
  
- [FastAsyncWorldEdit](https://github.com/IntellectualSites/FastAsyncWorldEdit) by [@boy0001](https://github.com/boy0001)

  > Fork of WorldEdit that operates asynchronously for higher performance.
  
- [WorldGuard](https://github.com/EngineHub/WorldGuard) by [@sk89q](https://github.com/sk89q)

  > Plugin and API to manage and protect custom areas of Minecraft worlds.
  
- [Slime-World-Manager](https://github.com/Grinderwolf/Slime-World-Manager) by [@Grinderwolf](https://github.com/Grinderwolf/)

  > Implementation of the Slime Region Format, developed by the Hypixel Dev Team.
