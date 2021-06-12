# Creating a Command

Creating a command is very easy. We use js objects to define description, function to execute the command, etc.

You need to create a js object with keys and values.

Take a look at [sample.js](https://github.com/Welcome-Bot/welcome-bot/blob/main/src/commands/sample/sample.js) before starting.

To create a command, run `npm run --cat=category --command=commandName`

Available categories are:
- admin
- bot
- info
- mod
- owner

To create a category, create a folder under the commands directory

The keys in the js object are described below:

## name

Command name

- Type: string
- Required: true

## aliases

Aliases for that command

- Type: array
- Required: false

## description

Description of that command

- Required: false

## permissions

Permissions required by a member/user to execute this command

- Type: array
- Required: false

## bot_perms

Permissions required by bot to execute this command

- Type: array
- Required: false

## args

Is at least 1 argument required

- Type: boolen
- Required: false

## guildOnly

Should we only execute this command in guilds and not DMs

- Type: boolen
- Required: false

## catchError

Do you want to catch error, log it and reply that there was an error

- Type: boolen
- Required: false

## usage

How to use this command.

- Type: string
- Required: false

## disabled

Is this command disabled

- Type: boolen
- Required: false

## subcommand

Is at least 1 subcommand required

- Type: boolen
- Required: false

## subcommands

What subcommands does this command have

- Type: array
- Required: false

## cooldown

Minimum time required to execute the same command again (default: 3)

- Type: int
- Required: false

## ownerOnly

Can only the owner(s) of this bot execute this command

- Type: boolen
- Required: false

## execute(message, args)

The function to execute the command, there are 2 args passed to this command when executing this command

- Type: function
- Required: true
