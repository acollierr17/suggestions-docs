---
description: >-
  So you're ready to invite the bot, but a bit confused? That's alright, start
  reading below!
---

# Invite & Setup

{% hint style="info" %}
Keep in mind you **must** have the`MANAGE SERVER`or`ADMINISTRATOR`permissions to be able to invite a bot to your server.
{% endhint %}

## Invite the Bot

To invite the bot, you must use [this link](https://discordapp.com/oauth2/authorize?client_id=474051954998509571&scope=bot&permissions=93248).

Here you can choose the server you wish to invite the bot to and choose what permissions. It is best to leave the permissions alone or you'll most likely run into issues. The bot is only assigned the permissions it needs. Those permissions are:

* Read Messages & View Channels \(`VIEW_CHANNEL`\)
* Send Messages \(`SEND_MESSAGES`\)
* Manage Messages \(`MANAGE_MESSAGES`\)
* Embed Links \(`EMBED_LINKS`\)
* Read Message History \(`READ_MESSAGE_HISTORY`\)
* Add Reactions \(`ADD_REACTIONS`\)

## Set Up the Bot

Once the bot is in your server, there are a few housekeeping things you need to do \(you must have the`MANAGE_GUILD`permission to complete these steps\).

Also by default, the prefix is`,`and the bot searches for`#suggestions`as the default user suggestions channel and`#suggestions-logs`as the default logs channel if a custom ones aren't set. The bot mention \(`@Suggestions#2602`\) can be used as a prefix for commands as well if you ever incorrectly set the prefix or forgot the prefix in general.

1. Create and set a user suggestions channel doing`setchannel <channel>`\(you can tag the channel\)
   1. Add the bot to that channel and exclusively give it the`SEND MESSAGES`and`ADD REACTIONS`permissions \(add anymore depending on what permissions you gave the bot globally\).
   2. Disable`SEND MESSAGES`and`ADD REACTIONS`for`@everyone`to keep the channel clean and that users only vote with the configured emoji set \(ex. the ✅ and ❌emojis\).
2. Create and set a suggestions log channel doing`setlogs <channel>`\(you can tag the channel\)
3. Add roles so users in that role can approve/reject user suggestions. You may do that with`role add <role>`where the role can either by tagged or typed out if it exists in the guild
4. Choose an emoji set for your guild. You can view the available sets via the `setvotes` command and choose which one you want in your guild with `setvotes <#>` where `#`indicates which emoji option.

Once you completed those steps, you should be set to go! Continue on to the [Managing Suggestions](managing-suggestions.md) page with information on approving/rejecting user suggestions.

