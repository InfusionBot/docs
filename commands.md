---
layout: docs
---

# Commands - Discord Welcome-Bot

> Default Prefix: `w/`

If You're not sure what prefix is used you can just `@-mention` the bot (`@welcome-bot#0914`) and it will tell you what prefix is used. If you though set a custom prefix for your server the default prefix can always be used.

- - -

{% include commands.md %}

- - -

All these commands should be prefixed with the prefix i.e. for command `ping` you have to send `w/ping` in the channel the bot has perms to read and send messages.

In some of these you will see under a command their is a subcommand, to execute those, send `command subcommand args` where `command` is the command, `subcommand` is the subcommand and `args` is/are the argument(s)

Example usage of subcommand: `w/message set Welcome {mention}!`

- - -

## Placeholders in welcome message
There are some placeholders you can use in the welcome message which will be replaced by their values by the bot.

Example: `{server}` will be replaced by the server's name

Available placeholders:
- `{server}` - The server's name
- `{mention}` - @-mention the user who has joined.
- `{members}` - The number of the member, took from members count in the server, i.e "If their were 8 members and a new member joins, he is our 9th member!"

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
