---
layout: docs
---

# Self-hosting - Welcome-Bot

**We ask you to please not host your own instance of Welcome-Bot.**
Even though our license allows it, self-hosted instances of the bot have brought us a lot of headache in the past.
If you're considering self-hosting, please [try the official instance of the bot first](https://dsc.gg/welcome-bot).
If you have any concerns about the security of our instance, please contact us.
We'd love to talk and answer any questions you have.

> If you're really really really going to self-host the bot, please [read our license][license] first, and be aware that we don't provide any self-hosting support which is up to date. You'll be on your own.

> The self-hosting docs below are archived, you may host older versions of Welcome-Bot, I am sure v1.5 and older will work, but not after that version.
> By self-hosting, you are losing a lot of features, we recommend to not self host your own instance of Welcome-Bot.

Some of you may want to self-host the bot on your own VPS/server.
This page explains how you can self-host the bot for yourself.

*Important!*
**By selfhosting the bot will you agree to the following terms:**
- You follow the [LGPL-v2.1-License][license] of the bot.
    - This means that you give credit to the original author (Welcome-bot team & contributors) and won't claim this code as your own.
- You aknowledge and agree that you won't receive any support for your self-hosted bot.

## Requirements
Before you can run the bot will you need to make sure that the following requirements are met.

### MongoDB
You need to have [MongoDB](//mongodb.com) installed and running on your server, where the bot will later run.

### Node
You need **at least** Node 12 to be installed and working. Newer versions of Node should work too.

### Get source code
Just run `npm i welcome-bot` to install using npm **OR** you can download archive from [releases] page.

### .env
The `.env` is the environment vars of the bot in which you set various different information that will be used by the bot.
To create it, first copy `.env.example` as `.env`, then add your bot token

Note that you don't have to set values for every option in `.env` file.
If you followed the previous step on preparing the bot will you only need to set the following options:

| Option:                | Value required:                                                                   |
| ---------------------- | --------------------------------------------------------------------------------- |
| `NODE_ENV`             | Better to set this to `production` when self-hosting                              |
| `BOT_TOKEN`            | Valid Bot-token of your Bot-application to login.                                 |
| `MONGODB_URL`          | Valid URL provided by MongoDB when creating DB.                                   |
| `BOT_PREFIX`           | Default prefix of the bot                                                         |

[license]: https://github.com/Welcome-bot/welcome-bot/blob/main/LICENSE
[releases]: https://github.com/Welcome-bot/welcome-bot/releases
