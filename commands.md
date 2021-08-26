---
layout: docs
---

# Commands - Discord Welcome-Bot

> Default Prefix: `w/`

If You're not sure what prefix is used you can just `@-mention` the bot (`@Welcome-Bot#0914`) and it will tell you what prefix is used.
You can set a custom prefix for your server, but the default prefix can always be used.

- - -

{% include commands.md %}

- - -

All these commands should be prefixed with the prefix i.e. for command `ping` you have to send `w/ping` in the channel the bot has perms to read and send messages.

Also note that `User` and `Member` are different, whenever there is `Member` in a command usage that means only people which are in the server can be used, while `User` is global therefore this bot just requires that user to be in the bot's cache.

In some of these you will see under a command their is a subcommand, to execute those, send `command subcommand args` where `command` is the command, `subcommand` is the subcommand and `args` is/are the argument(s)

Example usage of subcommand: `w/message set Welcome {mention}!`

- - -

## Placeholders in welcome & goodbye message
There are some placeholders you can use in the welcome & goidbye message which will be replaced by their values by the bot.

Example: `{server}` will be replaced by the server's name

Available placeholders:
- `{server}` - The server's name
- `{mention}` - @-mention of the user who just joined.
- `{members}` - New member count, or the count of total members
- `{members_formatted}` - Member count but formatted, example: `1st`, `2nd`, `10th`

- - -

## Images

### Welcome users

![Welcome users image]({{ '/assets/img/welcome.png' }})

### Paginated help

![Paginated help image]({{ '/assets/img/help.png' }})

### Get changelog on latest version!

![Changelog image]({{ '/assets/img/changelog.png' }})

### Random waifu image

![Waifu image]({{ '/assets/img/waifu.png' }})
