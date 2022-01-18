---
title: "PteroBot: Commands"
layout: default
permalink: /pterobot/commands
---

Here is a complete list of all commands.

Note to switch between parameters in a command, press the tab key.

# Server Owner Commands

### /Configure [APIUrl] [APIKey]

Initial configure of a server. No other Owner or admin commands will work untill this is complete.
Details for this command are on the [Setup](../../pterobot/setup) page.

### /Add-server [ServerID] [ServerName] [ServerType]

Links a minecraft server to your discord. Name must be unique.
Details for this command are on the [Setup](../../pterobot/setup) page.

### /Del-server [ServerName]

Deletes a minecraft server from your discord database.
**ServerName** is the name defined during the /add-server command

# Admin Commands

### /Whitelist [Action] [User]

Add or remove a user from whitelist. 
**Action** has 2 options to select from: Add or Remove.
**User** is a DISCORD user, not their name.

### /Power [State] [ServerName]

Change the power state of a server.
**State** has 3 options to select from: Start, Stop and Restart.
**ServerName** is defined during the /add-server command.

# User Commands

### /Gamertag [Gamertag]

Links your XBox Live gamertag to your discord account. This is stored globally and can be used on any server this bot serves.

### /Javaname [Javaname]

Links your in-game java name to your discord account. This is stored globally and can be used on any server this bot serves.
