---
description: >-
  You invited and set up the bot. Now users in your guild have submitted some
  suggestions. What do you do? Read more below.
---

# Managing Suggestions

_**Key:**_  
`< >` = Required  
`[ ]` = Optional

Managing suggestions are simple. Each suggestion is assigned a **Suggestion ID** \(sID\). From there, staff members can either reject or approve a suggestion with the sID. The sID is located in the footer of each suggestion: 

![Suggestion Example w/ sID](.gitbook/assets/2yycffh.png)

![Suggestion DM](.gitbook/assets/gjwhotb.png)

## Approving Suggestions

Suggestions are approved via the sID. Once you have it, run the command`approve <ID>`. Afterward, series of actions will happen:

* The suggestion will update as "Approved" in the suggestions channel and shortly delete itself afterward
* The user will receive a DM that you approved their suggestion
* The results of that suggestion will be logged in the suggestions logs channel
* _An optional response can be added doing_  `approve <ID> [response]`

![Suggestion Approved Status](.gitbook/assets/avibvld.png)

![Suggestion Approved DM](.gitbook/assets/b7ri3eb.png)

It seems like a lot doesn't it? It really isn't because it all happens in the matter of seconds!

## Rejecting Suggestions

Rejecting suggestions work the same way as approving suggestions. Once you run the command`reject <ID>`the same series of actions will happen as stated above, just instead information of the suggestion being rejected will be posted.

![Suggestion Rejected Status](.gitbook/assets/todtkn4.png)

![Suggestion Rejected DM](.gitbook/assets/yi57jj3.png)

## Suggestions Logging

When a suggestion is approved or rejected, it's results are logged to the suggestions logs channel you set earlier. In that channel, you'll find this information for each result:

* The results \(both UpVotes and DownVotes\)
* The suggestion
* The submitter
* The staff member that approved or rejected the suggestion
* The sID
* An optional response can be added doing `approve <ID> [response]`

![Suggestion Results](.gitbook/assets/nadwjuo.png)

## Suggestions Emojis

A newly introduced feature as of September 29, 2018, you have the ability to choose from a predefined list of emojis to be used for your suggestions. Setting this up is really simple. To see the available options as well as the option you have configured,  use the command `setvotes`

![The available emoji set.](.gitbook/assets/f7fsjcx.png)

To change to any of these options, you can simply do `setvotes <#>`\(ex. `setvotes 2`\). The number is in front of each emoji set. Upon changing, any future suggestions will use that emoji set, as shown below:

![An example of one of the emoji sets.](.gitbook/assets/gwe9so7.png)

## Suggestion Notes

A newly introduced feature as of December 2, 2018, you have the ability to add notes to a submitted suggestion. Notes can be used to not only notify the submitter of a suggestion about a change or improvement, but also notify the community as well.

![An example of a suggestion note](.gitbook/assets/qbsdxop.png)

To add a note to a suggestion, simply retrieve the sID and do `note <sID> <note>` where the `note` can be any message you wish to choose. Upon adding a note, the submitter of the suggestion will receive a DM with that information:

![An example of a suggestion note in DM](.gitbook/assets/g7xehmx.png)



