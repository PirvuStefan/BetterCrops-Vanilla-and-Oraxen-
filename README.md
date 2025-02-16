# BetterCrops-Vanilla-and-Oraxen-

Version for vanilla and Oraxen/ItemsAdder/Nexo compatibility ( works with every custom plugin that enables minecraft:tag feature )

# Compatibility

Paper 1.21+ and at least Java 21

(might not work with Paper 1.21.4 because of the new content update, but i believe will still do )

Paper is a fork of spigot, which is a fork of bukkit on its own .
View documentation for [paper](https://docs.papermc.io/) .
This will work on any fork of paper ( Folia, Pufferfish, Purpur ) .

# Dependencies

[NBT API](https://www.spigotmc.org/resources/nbt-api.7939/) ( at least version 2.14.1 )

This is a soft dependency, you can stil use the plugin without it, but the compatibility with Oraxen/ItemsAdder/Nexo will not work .
`Tag_Integration`  and `ItemList` will not work at all without it. ( view the `config.yml` ) .

# How to use

Drag the `bettercrops.jar` file into the plugin directory and start the server by running the `run.bat` or `run.sh` file ( windows/macos ) or run the `server.jar` file if you do not have a running configuration .
Upon the first run, it will create a direcory called BetterCrops with a `cofig.yml` file. Do not change the name of those .

```text
/
│
├── plugins/
│   ├── BetterCrops/
│      └── config.yml       
└── 
```

# Commands

```sh
/bettercrops reload
```

After modifing the `config.yml` , run this command by a player/terminal . If you do not run the command, the changes will take place only on restart .

This version does not work with the BetterCrops plugin, because at the moment I do not know how to integrate the API for that .
Will be available on polymc and spigotmc ( if I decide to port it to spigot ) .

Take care .
