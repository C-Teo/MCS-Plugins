![Creator Showdown Logo](/Images/logo.png)
# Overview

> This repository is simply made to discuss the plugins developed for Creator Showdown, a Minecraft tournament that is live streamed once every month. Since the plugins have to be privated in the GitHub Team, I just shortly discuss them here. If there is any section that you believe is underdetailed, please open an Issue and I'll take a look at it.

These plugins were created by a diverse team of programmers that changed in members throughout the development of the games. The games I've included here are the ones that I participated in as the Head Developer of the team. 

# Champion Crusader 🏰
Version: **1.16 - 1.18.2**\
Functionality: **Classes, Arenas, PVE Components, Capture Points, Respawn System**
> This game was our first ever developed plugin on the server. It was a great learning opportunity for myself as it was my first large scale plugin. Because of this, a lot of the code was over simplified since I had to use it as a teaching model for the developers who were learning the Spigot library. 

This program is definitely the one I’ll be spending a lot of time optimizing and refactoring in a later Server Update. It currently utilizes a lot of HashMaps and Data Packs uploaded onto the server that I want to rewrite as OOP instead. As a good practice, I’ve been slowly progressing through and commenting on every confusing or complicated aspect of the code. This plugin also implements the LuckPerms API inside itself so we could change player teams using our own set team command. Later we plan to program a Bungee API plugin that can keep track of all teams with loads of functionality so all plugins can access that instead.

# Crypt Crawler 🔦
Version: **1.18.2**\
Functionality: **Crafting, Bosses, PVE Components, Custom Items, Timer, Respawn System**
> Crypt Crawler is currently our most connected plugin as it utilizes many other Open Source plugins to be able to work very smoothly. It took a lot of time to properly connect the different plugins together especially when taking consideration of the need for compatibility in our custom code.

*This plugin is currently working alongside Mythic Mobs, Dungeons XL, Craft Enhance, and Luck Perms to be able to function properly.*

Mythic Mobs allows us to script our own bosses with enhanced functionality and loot tables that we are currently using for the boss and other entities. Craft Enhance just lets us edit the legacy crafting system and add our own custom designs. Dungeons XL is used with our own modeled dungeon to properly set up repeatable instances that will run when the game starts. This way every team is capable of running their own instance without interfering with the original copy or other team. Our plugin uses Luck Perms with OOP to properly incorporate teams that connect in our plugin to the Dungeons XL API. Some parts currently run through the console and that is the biggest part I want to improve later on. 

# Knockout 🥊
Version: **1.18.2**\
Functionality: **World Edit, Power-Ups, Custom Panels, Revival System**
> Editing Info...

# Trades and Ghouls 🧟‍♂️
Version: **1.18.2**\
Functionality: **PVE Waves, Vendor Interface, Purchasable Buffs and Equipment, Revival System**
> In Progress...

# Clutch City 🏙
> Future Project...
