---
layout: docs
---

# Creating a Command

Creating a command is very easy. We use js objects to define description, function to execute the command, etc.

You need to create a js object with keys and values.

To create a command, run `npm run mkcmd --cat=category --command=commandName`

Available categories are:
- setup
- general
- music
- mod
- fun
- owner
- core

To create a category, create a folder under the commands directory

The opts you provide when using the `super()` built-in function in the js class which extends Command are described below:

## name

Command name

- Type: String
- Required: true

## aliases

Aliases for that command

- Type: Array<String>
- Required: false

## memberPerms

Permissions required by a member/user to execute this command

- Type: Array
- Required: false

## botPerms

Permissions required by bot to execute this command

- Type: Array
- Required: false

## requirements

Requirements of the cmd.

- requirements.args: Are arguments required?
    - Type: Boolen
    - Required: false
- requirements.guildOnly: Does this cmd not work in DMs?
    - Type: Boolen
    - Required: false
- requirements.subcommand: Is at least 1 subcommand required
    - Type: Boolen
    - Required: false
- requirements.ownerOnly: Can only the owner(s) of this bot execute this command
    - Type: Boolen
    - Required: false

- Type: Object
- Required: false

## usage

How to use this command.

- Type: String
- Required: false

## disabled

Is this command disabled

- Type: Boolen
- Required: false

## subcommands

What subcommands does this command have

- Type: Array<Object>
- Required: false

## cooldown

Minimum time required to execute the same command again (default: 3)

- Type: Number
- Required: false

## category

The category of that command

- Type: String
- Required: true

## execute(message, args)

The function to execute the command, there are 2 args passed to this command when executing this command

- Type: Function
- Required: true
