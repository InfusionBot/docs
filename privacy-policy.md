---
layout: docs
---

# Privacy Policy - Welcome-Bot

Last updated and effective: 17 September 2021

By using Welcome-Bot, you agree to the following privacy policy.

*The Welcome-Bot website does not directly store data but uses Google Analytics, see [Analytics Privacy Info](https://policies.google.com/technologies/partner-sites).*

## Usage of Data

The bot may use stored data, as defined below, for different features including but not limited to: Welcoming joining users (when enabled) and command handling.
No usage of data outside of the aformentioned cases will happen and the data is not shared with any 3rd-party site or service.

## Stored Information

The bot may store the following information automatically when being invited to a new Discord Server:

- `guildId` with the `Server's ID` as value.
- `prefix` with value `w/`.
- `plugins.welcome.channel` with value `member-log`
- `plugins.welcome.message` with value `Welcome {mention} to the {server} server!\nYou are our #{members_formatted} member`
- `plugins.welcome.enabled` with value `true`
- `plugins.goodbye.channel` with value `null`
- `plugins.goodbye.message` with value `Good Bye {mention}!\nWe are sad to see you go!\nWithout you, we are {members} members`
- `plugins.goodbye.enabled` with value `false`
- `plugins.autorole.role` with value `0`
- `plugins.autorole.enabled` with value `false`
- `plugins.modlogs` with value `mod-log`
- `plugins.autopublish` with value `false`
- `disabled` with value `[]`
- `lang` with value `Server's preferred locale` given by discord, if that's missing then `en-US`

No other information outside of the above mentioned one will be stored.

## Updating Data

The data may be updated when using specific commands.
Updating data will require the input of an end user and data that can be seen as sensitive, such as content of a message, may need to be stored when using certain commands.

No other actions may update the stored information at any given time.

## Temporarely stored Information

The Bot may keep the stored information in an internal cacheing mechanic for a certain amount of time.
After this time period, the cached information will be dropped and only be re-added when required.

Data may be dropped from cache pre-maturely through actions such as removing the bot from the Server.

## Removal of Data

Stored Data may be removed by either removing the bot from a Server, through the means of kicking or banning it, or by requesting the removal of the data through E-Mail.
We reserve the right to ask for verification of Ownership of the Server, if removal was requested through E-Mail to prevent any possible abuse. This means that only the Server owner may ask for the removal of data from their Server through E-Mail.
E-Mail requests should go towards abhijoshi2k@gmail.com or baalkrshna@gmail.com.

### Limitations

We try our best to remove the data when needed but due to the nature of the bot may it happen that through certain periots of time, such as when the bot undergoes maintenance and therefore is offline, or when there is an issue with the host or Service Provider (Discord) causing connection-issues, that the stored data won't get removed correctly.
In such cases may you request the manual removal through E-Mail with the conditions as described above.

For this, we have set up db auditor, it runs every 3 hours. We can assure you 99.9% that within 3 hours the data will be removed from db if the bot came back online.
