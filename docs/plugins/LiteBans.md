---
id: Litebans
title: Litebans
hide_title: true
hide_table_of_contents: false
sidebar_label: Litebans
description: Litebans is a premium plugin to manage and distribute punishments on your server or network.
keywords:
  - Litebans
  - Punishment
  - Ban
  - mute
  - kick
  - Spigot
  - Bloom.host
  - Pterodactyl Panel
  - Minecraft
image: https://bloom.host/assets/images/logo.png
---
# **Litebans**

## What does the plugin do?

Litebans is a premium plugin that allows you and your server staff to manage and distribute punishments to your players.

## Usage
First, download the [Litebans](https://www.spigotmc.org/resources/nuvotifier.13449/) plugin and install it into your `plugins` folder.   

Next, you have to decide what type of storage you want for all your punishments, your options are H2, MySQL, MariaDB, and PostgreSQL. On Bloom you are going to want to use H2, or MySQL. H2 will store the information on your server, while MySQL will store it on a separate database. MySQL allows you to sync data accross a network if you are running one. Otherwise its your choice.

If you are using MySQL, you can see how to set up Litebans with MySQL [HERE](https://docs.bloom.host/databases)

## Commands
Litebans offers many commands to moderate your server, below will be a short list of the important ones.
```
/ban
/kick
/mute
/warn
/history
```
The ban command disalows the affected player from joining the server for the specified time.
The syntax for the ban command is /ban (-s) {Player} [Time] [Reason]
If no time is specified, it will be permanant, if no reaspon is provided, it will default to whatever is listed in the config.

The Kick command kicks the player off of the server, they wont be prevented from joining again
The syntax for the kick command is /kick {Player} [Reason]
If no reaspon is provided, it will default to whatever is listed in the config.

The ban command disalows the affected player from speaking in chat for the specified time.
The syntax for the ban command is /mute (-s) {Player} [Time] [Reason]
If no time is specified, it will be permanant, if no reaspon is provided, it will default to whatever is listed in the config.

The warn command will send the targeted player a message in chat, and if enabled in the config, deal a punishment automatically on a certain number of warns.
The syntax for the warn command is /warn (-s) {Player} [Reason]
A reason is required for a warn.

The history command displays the punishment history of a given player, this includes all kicks, mutes, warns, and bands the player has recieved.
The syntax for the history command is /history {Pllayer}

You may notice some of the commands have a (-s) in the syntax, if you put -s in that spot when executing the command it will silently execute the command. When done silently only players with a certain permission will see the punishment, otherwise everyone online will see it. 

## Links

[Litebans Spigot](https://www.spigotmc.org/resources/nuvotifier.13449/), Requires Account.

[Litebans Official Wiki](https://gitlab.com/ruany/LiteBans/-/wikis/home)

