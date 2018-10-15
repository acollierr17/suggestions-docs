---
description: >-
  Here you can view all the commands of the bot along with further configuration
  features.
---

# Full Commands

Forgot the prefix or incorrectly set one? All commands by default use`,`as the prefix or the bot mention \(`@Suggestions#2602`\).

_**Key:**_  
`< >` = Required  
`[ ]` = Optional

* `approve` - Approve a user suggestion \(with an optional response\)
  * Usage `approve <id> [response]`
  * _Requires a staff role or the`MANAGE_GUILD`permission_
* `blacklist` - Add or remove a user from the guild blacklist restricting them from using any of the `@Suggestions#2602` commands
  * Usage `blacklist <add/remove> <userID> [reason]`\*
  * _Requires the `MANAGE_GUILD` permission_
  * _\*Reason is only required when adding a user to the blacklist_
* `channel` - View the current user suggestions channel
* `help` - List all commands, current prefix and more information
* `info` - View information about the bot
* `invite` - Get an invite link for the bot
* `ping` - Get the latency of the bot and API
* `prefix` - View the current bot prefix
* `reject` - Reject a user suggestion \(with an optional response\)
  * Usage: `reject <id> [response]`
  * _Requires a staff role or the`MANAGE_GUILD`permission_
* `setchannel` - Set the user suggestions channel
  * Usage: `setchannel <channel>`
  * _Requires the permission `MANAGE_GUILD`_
* `setlogs` - Set the suggestions logs channel
  * Usage: `setlogs <channel>`
  * _Requires the permission `MANAGE_GUILD`_
* `setprefix` - Set the bot prefix
  * Usage: `setprefix <prefix>`
  * _Requires the permission `MANAGE_GUILD`_
* `setstaffchannel` - Set the staff suggestions channel
  * Usage: `setstaffchannel <channel>`
  * _Requires the permissions `MANAGE_GUILD`_
* `role` - Add or remove staff roles
  * Usage: `staffrole <add/remove> <role>`
  * _Requires the permission `MANAGE_GUILD`_
* `staffsuggest` - Create a new staff suggestion
  * Usage: `staffsuggest <suggest>`
  * _Requires a staff role or the`MANAGE_GUILD`permission_
* `stats` - View statistics about the bot
* `suggest` - Create a new suggestion
  * Usage: `suggest <suggestion>`
* `roles` - View the current staff roles
  * _Requires the permission`MANAGE_GUILD`_
* `suggestions`- View information on the total number of suggestions in your guild, and the total amount approved and rejected\*
  * _Requires a staff role or the permission `MANAGE_GUILD`_
* `sid`- View the information of a specific suggestion via it's suggestion ID \(sID\)
  * Usage: `sid <id>`
  * _Requires a staff role or the permission `MANAGE_GUILD`_
* `setvotes`- Set which set of emojis you want to use in your guild for suggestions from a predefined list \(by default, the  ✅ and  ❌ emojis are used\). Use the command with no arguments to see the options and current configuration
  * Usage: `setvotes <#>`
  * _Requires the permission `MANAGE_GUILD`_
* `mysuggestions` - View your own suggestion information including the total number you submitted, how many were rejected/approved and the sID of your most recent suggestion

_\*Approved and rejected suggestions only counted since September 29, 2018._

