---
layout: default
title: Modmail - Options
parent: Modmail()
grand_parent: Function
permalink: /modules/function/modmail/options
---

# ModmailOptions
Options For A `Modmail()` Function

### Types
- [Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)

### Properties
| **Parameter** | **Type** | **Required** | **Default** | **Description** |
| ----- | ----- | ----- | ----- | ----- |
| token | [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | True | None | Token of the account to log in with | 
| inbox | [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | False | None | Modmail inbox channel id |
| prefix | [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | True | None | Modmail bot’s prefix ( i.e. ! ) | 
| clientIntents | [array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/array) | True | None | Client Intents |
| message | [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | False | None | Sends that message before every mail |
| plugins | [array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/array) | False | None | Activate/Configure Plugins |
| resolve | [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | False | `all` | Item(s) To Resolve ([Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/promise)) |
| category | [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | False | None | Thread Category ID |
| roleID | [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | False | None | Modmail Staff Role ID |

