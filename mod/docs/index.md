# Moderator Documentation
## Roles
| Role Name                                       | Role Requirement                                                      | Role Perks                                                                                   |
|---------------------------------------|---------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| Regular (Tier 1)                                | MEE6 Level 3                                                          | Can send embedded messages in all channels, can change nickname                         |
| Regularly regular (Tier 2)                      | MEE6 Level 10                                                         | Access to #politics                                                                           |
| Superbly regularly regular (Tier 3)             | MEE6 Level 20                                                         | Can "Go Live" in a voice channel, access to #lounge                                           |
| Ludicrously superbly regularly regular (Tier 4) | MEE6 Level 30                                                         | Decorative                                                                                   |
| Uber regular (Tier 5)                           | MEE6 Level 45                                                         | Decorative                                                                                   |
| Hyper uber regular (Tier 6)                     | MEE6 Level 55                                                         | Access to Audit Log                                                                           |
| 💎 Nitro boosters                               | Boost the server with Discord Nitro                                   | Hoisted in sidebar, access to #lounge                                                       |
| Community Tech Support                          | Have Technical Queries Slayer, use !on-call command                   | Can be mentioned for assistance when necessary                                               |
| Technical Queries Slayer                        | Be extremely helpful in #tech-support                                 | Can pin and delete messages in #tech-support, as well as bypass its slowmode                  |
| Office Ninja                                    | Be helpful to users in #office channel                                | Can pin and delete messages in #office                                                       |
| Seasonal Logos Contributor                      | Have a lot of your server logo designs used                           | Decorative                                                                                   |
| Community Website/Wiki Contributor              | Contribute to the Community Website, Wiki                             | Decorative                                                                                   |
| Giveaways boss                                  | Host loads of awesome giveaways in #deals-and-giveaways               | Decorative                                                                                   |
| Muted                                           | Break rules or ask nicely                                             | Cannot talk anywhere in the server                                                           |
| Trial moderators                                | Apply for moderator position and be accepted                          | Access to moderator permissions; cannot ban                                                   |
| Moderators                                      | Be a good Trial moderator for a while                                 | Access to moderator permissions                                                               |
| Lead moderators                                 | Be a very good moderator for a very long time and have Kirby love you | Access to administrator permissions                                                           |
| /r/Windows moderator                            | Be a moderator on /r/Windows                                          | Decorative                                                                                   |
| /r/Surface moderator                            | Be a moderator on /r/Surface                                          | Decorative                                                                                   |
| /r/MicrosoftTeams moderator                     | Be a moderator on /r/MicrosoftTeams                                    | Decorative                                                                                   |
| 💌 Moderator's mail                             | Be the modmail bot                                                    | Decorative                                                                                   |
| 🌟 Microsoft employees                          | Verify in #ms-employee-verification                                   | Access to #msft-chat                                                                         |
| Alumni Microsoft employees                      | Stop being a Microsoft employee                                       | Decorative                                                                                   |
| Alumni moderator                                | Stop being a moderator                                                | Decorative                                                                                   |
| 💙 Edgevatars Event participant                 | Take part in the 2019 Edgevatars Event                                | Decorative                                                                                   |
| Coffee Club participant                         | Take part in the 2020 Coffee Club Event                               | Decorative                                                                                   |
| Minecraft Champion                              | Take part in the 2020 Minecraft Event                                 | Decorative                                                                                   |
| Windows Insiders (Release Preview)              | See the Commands section                                              | Receive notifications                                                                         |
| Windows Insiders (Beta)                         | See the Commands section                                              | Receive notifications                                                                         |
| Windows Insiders (Dev)                          | See the Commands section                                              | Receive notifications                                                                         |
| 💻 Patch Tuesday                                | See the Commands section                                              | Receive notifications                                                                       |

## Commands
Moderation commands are available through Cliptok and Dyno. Some commands are restricted to permanent moderators.
| Moderation Action            | Command                                          | Restriction           |
|------------------------------|--------------------------------------------------|-----------------------|
| Ban member                   | !ban <​member> [appeal¦duration] [reason]        | Permanent moderators  |
| Ban member, save messages    | !bankeep <​member> [appeal¦duration] [reason]    | Permanent moderators  |
| Unban member                 | !unban <​member>                                 | Permanent moderators  |
| Kick member                  | !kick <​member> [reason]                         | All moderators        |
| Mute member                  | !mute <​member> [duration] <​reason>             | All moderators        |
| Unmute member                | !unmute <​member>                                | All moderators        |
| Warn member                  | !warn <​member> <​reason>                        | All moderators        |
| Anonymously warn member      | !anonwarn <​channel> <​member> [reason]          | All moderators        |
| Edit member's infraction     | !editwarn <​member> <​warning ID> <​reason>      | Permanent moderators  |                      
| Remove member's infraction   | !delwarn <​member> <​warning ID>                 | Permanent moderators  |
| Display member’s infractions | !infractions [member]                            | All members           |
| Clear messages               | !clear [member] <​number of messages>            | All moderators        |
| Dehoist                      | !dehoist <​users>                                | All moderators        |
| Activate slow mode           | !slowmode <​duration¦off>                        | All moderators        |
| Display server info          | !server-info                                     | All members           |
| Display role info            | !role-info <​role name>                          | All members           |
| Display member info          | !user-info [member]                              | All members           |

## Auditing
Events are logged in the four logging channels as well as the Discord Audit Log.
### #user-logs
* Member joined
* Member left
* Member joined voice channel
* Member left voice channel
* Member switched voice channel
* Member posted invite
* Role assigned
* Role revoked
* Nickname changed

### #mod-logs
* Member banned
* Member unbanned
* Member kicked
* Member muted
* Member unmuted
* Member warned
* Member warning revoked
* Role created
* Role edited
* Role deleted
* Infringing message removed
* Server information updated

### #message-logs
* Message edited
* Message deleted
* Bulk message delete
* Channel created
* Channel deleted

### #vortex-logs
* Message edited
* Message deleted
* Bulk message delete dump
* Deleted media message content

### #modmail-logs
* Modmail thread openee
* Modmail thread closee
* Modmail thread close time
* Modmail thread log link

### Discord Audit Log
* Update server
* Create channel
* Update channel
* Delete channel
* Create channel permissions
* Update channel permissions
* Delete channel permissions
* Kick member
* Prune members
* Ban member
* Unban member
* Update member
* Update member roles
* Move member
* Disconnect member
* Add bot
* Create role
* Update role
* Delete role
* Create invite
* Update invite
* Delete invite
* Create webhook
* Update webhook
* Delete webhook
* Create emoji
* Update emoji
* Delete emoji
* Delete messages
* Bulk delete messages
* Pin message
* Unpin message
* Create integration
* Update integration
* Delete integration

## Modmail
When a user messages the modmail bot, it creates a new private channel in the Modmail category and notifies all active moderators (@here)
### Modmail Commands
| Modmail Action                            | Command                                     | Restriction     |
|-------------------------------------------|---------------------------------------------|-----------------|
| Reply anonymously                         | !anonreply, !ar <​message>                  | All moderators  |
| Block member from modmail                 | !block                                      | All moderators  |
| Display blocked members                   | !blocked                                    | All moderators  |
| Close thread                              | !close [silent] [in `time`] [reason]        | All moderators  |
| Create thread with member                 | !contact                                    | All moderators  |
| Edit message                              | !edit                                       | All moderators  |
| Display link to current thread’s logs     | !loglink                                    | All moderators  |
| Display member’s previous modmail threads | !logs                                       | All moderators  |
| Move thread to another category           | !move                                       | All moderators  |
| Take note about current thread            | !note                                       | All moderators  |
| Notify of next message received           | !notify                                     | All moderators  |
| Flag thread as NSFW                       | !nsfw                                       | All moderators  |
| Reply                                     | !reply, !r <​message>                       | All moderators  |
| Set up server for modmail                 | !setup                                      | Lead moderators |
| Display set snippets                      | !snippets                                   | All moderators  |
| Notify of every message received          | !subscribe                                  | All moderators  |
| Unblock member from modmail               | !unblock                                    | All moderators  |
| Stop being notified of messages received  | !unsubscribe                                | All moderators  |

### General Commands
| Bot Action                                  | Command    | Restriction     |
|---------------------------------------------|------------|-----------------|
| Display bot info                            | !about     | All moderators  |
| Set activity of bot                         | !activity  | Lead moderators |
| Display changelog of bot                    | !changelog | All moderators  |
| Display aliases                             | !alias     | All moderators  |
| Display help message                        | !help      | All moderators  |
| Change what bot mentions at start of thread | !mention   | Lead moderators |
| Test websocket latency                      | !ping      | Lead moderators |
| Change bot prefix                           | !prefix    | Lead moderators |
| Set status of bot                           | !status    | Lead moderators |

### Modmail Message Snippets
Send a message snippet by typing the prefix then the snippet name. For example, `!thanks` will automatically send the message "Thank you for reaching out!"
| Snippet Name   | Snippet                                                                                                                                        |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| baduse         | Using modmail inappropriately might lead to suspension                                                                                         |
| techsupport, ts| (As !ask)                                                                                                                                      |
| inactivity     | Hi, we're closing the thread due to inactivity. If you have any questions remaining feel free to re-open it, thank you!                        |
| thanks         | Thank you for reaching out!                                                                                                                    |
| accounts       | We do not have the access to assist with purchasing and account queries. Please contact official Microsoft support at support.microsoft.com.   |
| greeting       | ℹ Hello, welcome to Microsoft Community moderators mail. How may I help?                                                                       |
| the-rules      | https://go.msft.chat/rules                                                                                                                     |
| warned         | Thanks, this user has been warned!                                                                                                             |
| warn-limit     | [As in FAQ](https://msft.chat/member/#i-got-warned-how-many-times-can-i-get-warned-before-i-get-banned)                                        |
| questions?     | Do you have any other questions?                                                                                                               |
| modwhen        | [As in FAQ](https://msft.chat/member/#i-applied-to-become-a-moderator-how-long-before-i-get-an-answer)                                         |
| modapply       | [How Do I Apply to be a Moderator?](https://msft.chat/member/#how-do-i-apply-to-be-a-moderator)                                                |
| unofficial     | [As in FAQ](https://msft.chat/member/#is-this-server-official)                                                                                 |
| verifysuccess  | There you go, you should be able to interact with the server normally now. Make sure you've read our rules, and have fun!                      |


## Automated Actions

### Auto-Mute
Cliptok will automatically mute users after they pass a certain threshold of infractions in a given time:
| Trigger | Action                                                                                                                          |
|--------------------------------------------|----------------------------------------------------------------------------------------------|
| 2 infractions or more in the last 30 days  | Mute for 6 hours                                                                             |
| 4 infractions or more in the last 30 days  | Mute for 12 hours                                                                            |
| 6 infractions or more in the last 30 days  | Mute for 1 day                                                                               |

### Auto-Moderator
Bots will carry out these automated actions based on the following actions:
| Trigger                  | Action                                                                                                         | Bot       |
|--------------------------|----------------------------------------------------------------------------------------------------------------|-----------|
| Prohibited words         | Delete message, warn member                                                                                    | Cliptok   |
| Server invites           | Delete message, warn member<br>Allowed roles: Moderators, Tier 2 and above, Microsoft employees                | Cliptok   |
| Excessive emoji (> 7)    | Delete message, warn member<br>Ignored channels: #random-stuff                                                 | Cliptok   |
| Mass mention (> 4)       | Delete message, warn member                                                                                    | Cliptok   |
| Zalgo                    | Delete message<br>Allowed roles: Tier 3 and above                                                              | MEE6      |
| Toxicity                 | Delete message, mute member, alert moderators<br>Trusted members: two toxic messages in succession             | Dotsimus  |
