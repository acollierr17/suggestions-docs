---
description: >-
  Here you can view all the commands of the bot along with further configuration
  features organized by their permission categories.
---

# Full Commands

Forgot the prefix or incorrectly set one? All commands by default use`,`as the prefix or the bot mention \(`@Suggestions#2602`\).

_**Key:**_  
`< >` = Required  
`[ ]` = Optional

{% tabs %}
{% tab title="General Commands" %}
* `changelog` - View the recent changelog for the bot
  * Aliases: `changes, updates, changelogs`
* `help` - View bot commands and where to receive support
  * Aliases: `h, halp`
* `info` - View bot information
  * Aliases: `botinfo`
* `invite` - Receive a DM with information on inviting the bot to your server
  * Aliases: `bot, botinvite`
* `ping` - View the latency of the bot and API
  * Aliases: `pong`
* `prefix` - View the current bot prefix in the guild
* `stats` - View bot statistics
* `channel` - View the current suggestions channel in the guild
* `mysuggestions` - View your own suggestions data in the guild
* `sid` - View the information of a specific guild suggestion by their sID
  * Usage: `sid <`id`>`
* `suggest` - Submit a new suggestion
  * Usage: `suggest <suggestion>`
* `suggestions` - View suggestions data in the guild
* `vote`- View all links to vote for the bot on various bot list sites
* `patrons`- View all Patrons who have pledged to Nerd Cave Development
{% endtab %}

{% tab title="Staff Commands" %}
These commands require a staff role or the `MANAGE_GUILD` permission.

* `approve` - Approve a submitted suggestion via the suggestion ID \(sID\)
  * Usage: `approve <sID> [response]`
* `note` - Add a note to a submitted suggestion via the suggestion ID \(sID\)
  * Usage: `note <sID> <note>`
* `reject` - Reject a submitted suggestion via the suggestion ID \(sID\)
  * Usage: `reject <sID> [response]`
* `staffsuggest` - Submit a new suggestion for staff members to vote on
  * Usage: `staffsuggest <suggestion>`
{% endtab %}

{% tab title="Admin Commands" %}
These commands require the `MANAGE_GUILD` permission.

* `blacklist` - Add or remove a user from the bot blacklist \(guild-only\)
  * Usage: `blacklist <add/remove> <user ID> <reason>`\*
  * _\*Reason is only required for adding a user to the blacklist_
* `config` - View a text-based version of the bot configuration for the guild
  * Aliases: `conf, viewconf, viewconfig, settings`
* `role` - Add or remove staff roles for managing suggestions
  * Aliases: `staffrole`
  * Usages: `role add/remove <role>`
* `roles` - View the current staff roles for the bot
  * Aliases: `staffroles, viewroles, viewrole`
* `setchannel` - Set a new suggestions channel
  * Usage: `setchannel <channel>`
* `setlogs` - Set a logs channel for suggestion results
  * Usage: `setlogs <channel>`
* `setprefix` - Set a new prefix for the bot
  * Usage: `setprefix prefix`
* `setstaffchannel` - Set a new staff suggestions channel
  * Usage: `setstaffchannel <channel>`
* `setvotes` - Set custom emojis to use when voting
  * Usage: `setvotes <id>`
{% endtab %}
{% endtabs %}



