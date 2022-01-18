---
title: "PteroBot: Setup"
layout: default
permalink: /pterobot/setup
---

Setting up PteroBot to work on your server is very simple!

### Adding to discord

To add the bot to a discord server, you must have the "Manage Server" or "Administrator" permission. You can then add it by [**Clicking Here**](https://discord.com/api/oauth2/authorize?client_id=931474152777474078&permissions=0&scope=bot%20applications.commands)

### Configuring the bot

Once the bot is on the discord server, the server owner can configure the bot using the **/configure** command as follows:

<img src="../../assets/img/pterobot/configure.png" alt="Configure Screenshot"/>

__Parameters__

APIUrl: This can be taken from your host. Please do **not** include the trailing slash.
* Known API Urls:
    * Cluckhost: https://panel.cluckhost.com

APIKey: This is generated in your hosting panel under account settings and API Credentials. When creating an API key, either leave allowed IP's blank, or enter **89.40.12.101** which is the bots IP Address.

*Note when using slash commands, press tab after entering a parameter to move to the next parameter.*

### Adding a minecraft server

Once configured, you can start adding minecraft servers to the database using the **/add-server** command:

<img src="../../assets/img/pterobot/add-server.png" alt="Add-Server Screenshot"/>

__Parameters__

ServerID: This is the unique server ID to identify the server on your panel. It can be found in the address bar when viewing a server console as url.url/server/**SERVERID**

ServerName: Server name to internally define your server. This must be unique and you'll need to remember this.

ServerType: Java or Bedrock. Choices are provided when entering this parameter

*Note when using slash commands, press tab after entering a parameter to move to the next parameter.*

### Final Notes

Your server is now configured to use. Check the [Commands](../../pterobot/commands) page for a full list of commands.