---
layout: default
title: Intents
parent: Function
grand_parent: Modules
has_children: true
permalink: /modules/function/intents
---

# Intents 
Data structure that makes it easy to calculate intents.

### Usage
```js
const { Intents } = require('modmail.js')
...
{
  clientIntents: [ Intents.FLAGS.GUILDS, Intents.FLAGS.GUILD_MESSAGES, Intents.FLAGS.GUILD_MESSAGE_REACTIONS, Intents.FLAGS.DIRECT_MESSAGES ]
}
```

### More Information
Read [Discord.js Docs](https://discord.js.org/#/docs/main/stable/class/Intents) To Learn More

