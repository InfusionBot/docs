Welcome-Bot contains more than **40 commands** in **10 categories**!

### **Usage Key!**

- The `[` and `]` around the argument mean it’s required.  
- The `(` and `)` around the argument mean it’s optional.

#### Contents in a command

**Name**: The name of the command  
**Subcommands**: Subcommands to that command if available  
**Description**: A brief explanation of the purpose of the command  
**Usage**: The arguments/options that the command takes in parameters  
**Aliases**: Duplicate names for this command which can be used.  
**Cooldown**: The time that must elapse between each command so that it can be executed again by the user

# Table of contents

- [Setup](#setup)
- [General](#general)
- [Information](#information)
- [Moderation](#moderation)
- [Miscellaneous](#miscellaneous)
- [Fun](#fun)
- [Anime](#anime)
- [Games](#games)
- [Owner Only](#owner-only)
- [Core](#core)



## Setup (7 commands)

### `channel`

##### Subcommands:

- `set` - Set Welcome channel
- `setMod` - Set Moderation channel
- `reset` - Reset Welcome channel
- `resetMod` - Reset Moderation channel

##### Cmd info

- Description: Manage channel settings for this server
Not providing any arguments will display the current settings.
- Usage: None
- Aliases: `chan`
- Cooldown: 10

### `disable`

##### Subcommands:

- `welcome` - Disable welcome logs
- `goodbye` - Disable goodBye logs
- `show` - Show current settings

##### Cmd info

- Description: Disable welcome and goodbye logs.
- Usage: [subcommand]
- Aliases: None
- Cooldown: 10

### `enable`

##### Subcommands:

- `welcome` - Enable welcome logs
- `goodbye` - Enable goodBye logs
- `show` - Show current settings

##### Cmd info

- Description: Enable welcome and goodbye logs.
- Usage: [subcommand]
- Aliases: None
- Cooldown: 10

### `follow`

##### Subcommands:

- None

##### Cmd info

- Description: Get news and version updates to this bot sent to a specific channel.
- Usage: [channel / channel id]
- Aliases: `getnews`
- Cooldown: 10

### `lang`

##### Subcommands:

- `list` - List of all languages available
- `set` - Set language

##### Cmd info

- Description: Change language
- Usage: (subcommand) (lang)
- Aliases: `language`, `changelang`, `getlang`
- Cooldown: 5

### `message`

##### Subcommands:

- `set` - Set Welcome message
- `reset` - Reset Welcome message

##### Cmd info

- Description: Manage welcome message for this server
- Usage: None
- Aliases: `msg`
- Cooldown: 10

### `prefix`

##### Subcommands:

- `set` - Set Custom prefix
- `reset` - Reset Custom prefix

##### Cmd info

- Description: Manage prefix for this server
- Usage: None
- Aliases: `getprefix`
- Cooldown: 10

## General (4 commands)

### `invite`

##### Subcommands:

- None

##### Cmd info

- Description: Get Invite link for the bot
- Usage: None
- Aliases: None
- Cooldown: 20

### `ping`

##### Subcommands:

- None

##### Cmd info

- Description: Ping the bot
- Usage: None
- Aliases: `latency`
- Cooldown: 5

### `help`

##### Subcommands:

- None

##### Cmd info

- Description: List all commands or get info for a specific command/category.
- Usage: (command name / category)
- Aliases: `commands`, `cmd`
- Cooldown: 5

### `perms`

##### Subcommands:

- None

##### Cmd info

- Description: Get permissions given to a specific user. Not providing any user mention will show your permissions
- Usage: (@mention / user_id)
- Aliases: `permissions`
- Cooldown: 5

## Information (5 commands)

### `avatar`

##### Subcommands:

- None

##### Cmd info

- Description: Get a user's avatar
- Usage: (mention / user id)
- Aliases: `dp`, `profile`
- Cooldown: 5

### `botinfo`

##### Subcommands:

- None

##### Cmd info

- Description: Bot information
- Usage: (--dm)
- Aliases: `botstats`, `info`
- Cooldown: 10

### `stats`

##### Subcommands:

- None

##### Cmd info

- Description: Your server statistics
- Usage: (--dm)
- Aliases: `server`
- Cooldown: 10

### `user`

##### Subcommands:

- None

##### Cmd info

- Description: Get information about a user. It will show your info if no user was mentioned
- Usage: (@mention / user_id)
- Aliases: `whois`
- Cooldown: 3

### `version`

##### Subcommands:

- None

##### Cmd info

- Description: Get information on a version or latest version
- Usage: (version)
- Aliases: `ver`
- Cooldown: 10

## Moderation (4 commands)

### `ban`

##### Subcommands:

- None

##### Cmd info

- Description: Ban a user.
- Usage: [@user] (reason)
- Aliases: None
- Cooldown: 5

### `kick`

##### Subcommands:

- None

##### Cmd info

- Description: Kick a user.
- Usage: [@mention] (reason)
- Aliases: None
- Cooldown: 5

### `prune`

##### Subcommands:

- `all` - Delete 100 messages
- `bots` - Delete all messages sent by a bot in this channel
- `*[string]` - `*Text` will delete any message containing "Text"

##### Cmd info

- Description: Prune Messages.
- Usage: [no of msg to prune / subcommand]
- Aliases: `purge`
- Cooldown: 5

### `unban`

##### Subcommands:

- None

##### Cmd info

- Description: Unban a user.
- Usage: [user_id]
- Aliases: None
- Cooldown: 5

## Miscellaneous (2 commands)

### `qrcode`

##### Subcommands:

- `generate` - Generate a qrcode
- `read` - Read a qrcode

##### Cmd info

- Description: Generate or Read a QR code
- Usage: [subcommand] [data / image_url]
- Aliases: `qr`
- Cooldown: 10

### `test`

##### Subcommands:

- None

##### Cmd info

- Description: Test by sending welcome message
- Usage: None
- Aliases: None
- Cooldown: 3

## Fun (3 commands)

### `figlet`

##### Subcommands:

- None

##### Cmd info

- Description: Implement the FIGfont spec in JS
- Usage: [string]
- Aliases: `asciify`, `bigtext`
- Cooldown: 10

### `image`

##### Subcommands:

- None

##### Cmd info

- Description: Generate a random pokemon image
- Usage: None
- Aliases: `random-image`
- Cooldown: 10

### `pokemon`

##### Subcommands:

- None

##### Cmd info

- Description: Get a pokemon image
- Usage: [pokemon character]
- Aliases: `pokémon`
- Cooldown: 10

## Anime (5 commands)

### `cuddle`

##### Subcommands:

- None

##### Cmd info

- Description: Cuddle with a user
- Usage: [mention / user id]
- Aliases: None
- Cooldown: 3

### `hug`

##### Subcommands:

- None

##### Cmd info

- Description: Give a hug to a user
- Usage: [mention / user id]
- Aliases: None
- Cooldown: 3

### `kiss`

##### Subcommands:

- None

##### Cmd info

- Description: Kiss a user
- Usage: [mention / user id]
- Aliases: None
- Cooldown: 3

### `slap`

##### Subcommands:

- None

##### Cmd info

- Description: Slap a user
- Usage: [mention / user id]
- Aliases: None
- Cooldown: 3

### `waifu`

##### Subcommands:

- None

##### Cmd info

- Description: Fetches a random waifu and displays it.
- Usage: None
- Aliases: None
- Cooldown: 10

## Games (2 commands)

### `8ball`

##### Subcommands:

- None

##### Cmd info

- Description: Get your fortune by asking your question
- Usage: [question]
- Aliases: `eightball`
- Cooldown: 3

### `coinflip`

##### Subcommands:

- None

##### Cmd info

- Description: Flip a coin.
- Usage: None
- Aliases: `cf`
- Cooldown: 10

## Owner Only (4 commands)

### `eval`

##### Subcommands:

- None

##### Cmd info

- Description: Execute a JS statement.
- Usage: [statement]
- Aliases: None
- Cooldown: 20

### `reload`

##### Subcommands:

- None

##### Cmd info

- Description: Reloads a command
- Usage: [command]
- Aliases: None
- Cooldown: 30

### `restart`

##### Subcommands:

- None

##### Cmd info

- Description: Restart the bot
- Usage: None
- Aliases: None
- Cooldown: 30

### `servers-list`

##### Subcommands:

- None

##### Cmd info

- Description: Show the list of servers the bot is in.
- Usage: None
- Aliases: `slist`, `serverslist`
- Cooldown: 10

## Core (5 commands)

### `botperms`

##### Subcommands:

- None

##### Cmd info

- Description: List of permissions given to bot
- Usage: None
- Aliases: None
- Cooldown: 10

### `lib`

##### Subcommands:

- None

##### Cmd info

- Description: Library used to build Welcome-Bot
- Usage: None
- Aliases: `library`
- Cooldown: 10

### `support`

##### Subcommands:

- None

##### Cmd info

- Description: Get Support for Welcome-Bot
- Usage: None
- Aliases: `getsupport`
- Cooldown: 10

### `uptime`

##### Subcommands:

- None

##### Cmd info

- Description: Get uptime of the bot
- Usage: None
- Aliases: `getuptime`
- Cooldown: 10

### `website`

##### Subcommands:

- None

##### Cmd info

- Description: Link to Welcome-Bot's website
- Usage: None
- Aliases: `site`
- Cooldown: 10
