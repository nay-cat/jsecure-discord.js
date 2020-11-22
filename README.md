[![Foto JSecureNPM](https://cdn.discordapp.com/attachments/760909132370280469/761315999390892092/jscure.png)](https://www.npmjs.com/package/alpha-jsecure-discord)
# JSecure # discord.js
Add security commands without having to directly elbow them.
# Update 1.2.0
- Remove getSecureToken and setSecureToken
- Add Config Options
- +500 Forceban ID's 
# Añade comandos de seguridad sin necesidad de codearlos desde 0. 
# Add Security Commands

  - Iplogger Deleter +20 Detections
  - Forceban System +500 Raiders
  - Console Log Messages
  - Message Editor
  
# Próximamente / Soon
 - EventSystem Iplogger/Forceban
 - AddID to Forceban System

# Languages
  - Configurable
  - Spanish / Principal / First
  - English
# How to use ¿Cómo usar?

# Commands / Comandos
AntiIpLoggers
```js
// Need :: const jsecure = require ('alpha-jsecure-discord');
// Variables:
// %member% - Member send IpLogger // Example:
// jsecure.commandRemoveIpLoggers("message", "TOKEN");
jsecure.commandRemoveIpLoggers("%member% send a Iplogger", "TOKEN"); // Command Example
```
Forceban
```js
// Need :: const jsecure = require ('alpha-jsecure-discord');
// jsecure.commandForceBan("prefix", "forcebanCommandName", "TOKEN"); 
jsecure.commandForceBan("!", "forceban", "TOKEN"); // Command Example
```

# Example Bot Main / Bot Main Ejemplo
```js
const Discord = require('discord.js');
const jsecure = require ('alpha-jsecure-discord');

const client = new Discord.Client();

client.once('ready', () => {
    console.log('Iniciado');
});

jsecure.commandRemoveIpLoggers("%member% send a Iploggers", "TOKEN-OF-YOUR-BOT");
jsecure.commandForceBan("!", "forceban", "TOKEN-OF-YOUR-BOT");
client.login("TOKEN");
```
### Por cualquier bug avisame a discord / Bugs in Discord

[Dev's Lounge](https://discord.gg/CjZWhve) // Support Server 1 

[TutoBot](https://discord.gg/JGBkpM3) // Support Server 2
### In updates / Last Update: 10/10/2020
#### Si te gusta el npm, puedes seguirme en github // Follow me in GitHub

[Issues](https://github.com/xNayra/jsecure-discord.js/issues)

[Dev's Lounge](https://discord.gg/CjZWhve)

[GitHub](https://github.com/xNayra/)

#### Other Bots / Otros Bots / Other Servers
[TutoBot](https://discord.gg/JGBkpM3)
[SD Security](https://discord.com/oauth2/authorize?client_id=743056607499517952&scope=bot&permissions=8)