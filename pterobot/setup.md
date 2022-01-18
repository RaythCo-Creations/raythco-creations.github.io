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