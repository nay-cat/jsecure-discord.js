# jsecure-discord.js 
# https://www.npmjs.com/package/alpha-jsecure-discord

[![Logo](https://www.npmjs.com/package/alpha-jsecure-discord](https://cdn.discordapp.com/attachments/760909132370280469/761315999390892092/jscure.png)](https://www.npmjs.com/package/alpha-jsecure-discord)

# JSecure # discord.js
Add security commands without having to directly elbow them.

Añade comandos de seguridad sin necesidad de codearlos desde 0.

  - Iplogger Deleter +20 Detections
  - Forceban System +50 Raiders
  - Console Log Messages
# Próximamente / Soon
 - EventSystem Iplogger/Forceban
 - AddID to Forceban System
 - MessageEditor

# Languages

  - Spanish / Principal / First
  - English
# How to use ¿Cómo usar?
```js
var jsecure = require('alpha-jsecure-discord')
jsecure.setSecureToken("TOKEN"); // Aquí va el token de tu bot | Here the token of your bot
```
# Commands / Comandos
AntiIpLoggers
```js
var jsecure = require('alpha-jsecure-discord')
jsecure.commandRemoveIpLoggers(); // Command
```
Forceban
```js
var jsecure = require('alpha-jsecure-discord')
jsecure.commandForceBan(); // Command
```

# Example Bot Main / Bot Main Ejemplo
```js
const Discord = require('discord.js');
const jsecure = require ('alpha-jsecure-discord');

const client = new Discord.Client();

client.once('ready', () => {
    console.log('Iniciado');
});

jsecure.setSecureToken("TOKEN");
jsecure.commandRemoveIpLoggers();
jsecure.commandForceBan();
client.login("TOKEN");
```
