---
layout: default
title: Modmail()
parent: Function
grand_parent: Modules
has_children: true
permalink: /modules/function/modmail
---

# Modmail
Logs the client in, establishing a websocket connection to Discord, then starts the bot.

```js
.Modmail(options)
```

| **Parameter** | **Type** | **Description** |
| ------------- | -------- | --------------- |
|  [Options / Configuration](./modules/function/modmail/options)     | Object   | Set Up / Configure The Modmail |

**Returns :** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise) <[object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/object)>

| Key | Value |
| ------ | ----- |
| **client** | [Discord.Client()](https://discord.js.org/#/docs/main/stable/class/Client) |
| **plugins** | Plugin Status |





