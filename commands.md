---
layout: article_fire
title: Fire - Commands
---

##### All of these examples use the default prefix, `$`

## MAIN COMMANDS


Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
ping | Shows you my ping to discord's servers | `$ping` | None
suggest | Suggest a feature | `$suggest <suggestion>` | None
invite | Sends my invite link | `$invite` | None
stats | Shows you some stats about me | `$stats` | None
rpc | View someone's rich presence | `$rpc [<member>]` | None
dab | dab. | `$dab` | None
warm | warm something up | `$warm <something>` | None
cowsay | Cow goes moo (or whatever really) | `$cowsay <text>` | None
ascii | Make ASCII text | `$ascii <text>` | None
👏 | Emphasise your text with clapping | `$clap <text>` | clap
8ball | Ask the magic 8ball a question | `$8ball <question>` | None

HYPIXEL
==============
###### The Hypixel command consists of different "subcommands", which are listed below.

Name | Description | Usage
---- | ----------- | -----
key | See my API key usage | `$hypixel key`
watchdog | See watchdog stats, usually broadcasted every 2 hours on the server | `$hypixel watchdog` 
skyblock | See SkyBlock news (profiles are a work in progress) | `$hypixel skyblock [<news>]`
player | Get a general overview of a player | `$hypixel <player>`
guild | Get a general overview of a player's guild & members | `$hypixel <player> guild`
friends | Get a general overview of a player's friends | `$hypixel <player> friends`

MINECRAFT COMMANDS
=================

Name | Description | Usage
---- | ----------- | -----
skin | See a player's Minecraft skin | `$skin <ign/UUID>`
mcstatus | Check the status of Minecraft services | `$mcstatus`

KSoft.Si COMMANDS
=================

Name | Description | Usage
---- | ----------- | -----
meme | Get a random meme | `$meme [<subreddit>]`
lyrics | Get the lyrics for a song (Provide a member to search for their current song on Spotify) | `$lyrics [<query/member>]`
image | Get an image from a tag | `$image <tag>`
imagetags | Get a list of tags (for the above command) | `$imagetags`
baninfo | Get info about a ban on KSoft.Si | `$baninfo <user id>`

SK1ER COMMANDS
=================

Name | Description | Usage
---- | ----------- | -----
levelhead | Get a player's levelhead info | `$levelhead <player>`
modcore | Get a player's modcore profile | `$modcore <player>`

HYPERIUM COMMANDS
=================
###### The Hyperium command consists of different "subcommands", which are listed below.

Name | Description | Usage
---- | ----------- | -----
stats | Get Hyperium's statistics | `$hyperium stats`
player status | Check if a player is currently using Hyperium | `$hyperium <player> status`
player purchases | Check a player's purchases | `$hyperium <player> purchases`

YOUTUBE COMMANDS
=================
###### The YT command consists of different "subcommands", which are listed below.

Name | Description | Usage
---- | ----------- | -----
yt | Get the top 5 trending videos in the US | `$yt`
yt info | Get a video's info from an ID or URL | `$yt info <id/url>`

MUSIC COMMANDS
=================

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
connect | Connect to a voice channel | `$connect <channel>` | join
play | Queue a song or playlist for playback. | `$play <search query/url>` | sing, p
np | Sends the music controller message which contains various information about the current and upcoming songs. | `$np` | now_playing, current, currentsong
pause | Pause the currently playing song. | `$pause` | None
resume | Resume a currently paused song. | `$resume` | None
skip | Skip the current song. | `$skip` | None
stop | Stop the player, disconnect and clear the queue. | `$stop` | None
volume | Change the player volume. | `$volume <number: 1-100>` | vol
queue | Retrieve a list of currently queued songs. | `$queue` | q, que
shuffle | Shuffle the current queue. | `$shuffle` | mix
repeat | Repeat the currently playing song. | `$repeat` | loop
seteq | Pick from one of the equalizer presets to change your music. | `$seteq <Flat/Boost/Metal/Piano>` | None

IMAGE GEN COMMANDS
=================

Name | Description | Usage
---- | ----------- | -----
makeameme | Make your own meme using the "top text, bottom text" format | `$makeameme <member/image url> <top text>/<bottom text>`
deepfry | Deepfry an image or your avatar (your avatar is used if no argument is provided) | `$deepfry [<member/image url>]`

SETTINGS COMMANDS
=================

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
settings | Run through my setup process to configure a few settings | `$settings` | setup
setlogs | Set a channel for logging | `$setlogs <channel>` | None
desctiption | Set the description for the server that shows in Vanity URLs | `$description <desccription>` | desc
modonly | Set channels to restrict commands for moderators | `$modonly [<**channels>]` | None
adminonly | Set channels to restrict commands for admins | `$modonly [<**channels>]` | None
joinmsg | Set the join message and a channel to send it in | `$joinmsg <channel> <message>` | None
leavemsg | Set the leave message and a channel to send it in | `$leavemsg <channel> <message>` | None
linkfilter | Enable different link filters. Run the command without arguments to see all filters | `$linkfilter <**filters>` | None
filterexcl | Exclude channels/roles/members from the filters | `$filterexcl <**channel/role/member>` | None
command | Enable/disable a command in your server | `$command <command>` | None

MODERATION COMMANDS
=================
###### Users with the `Manage Messages` permission are considered moderators and can use these commands. Be careful who you give this permission to

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
ban | Ban a user from the server | `$ban <user> [<reason>]` | banish, begone, gtfo, 410
unban | Unban a user from the server | `$unban <user> [<reason>]` | unbanish
softban | Bans a user, deletes messages from a specified amount of days and then unbans. | `$softban <user> <amount of days: 1-7> [<reason>]` | None
mute | Mute a user. | `$mute <user> [<time> <reason>]` Time format: 1d 2h 3m 4s == 1 day, 2 hours, 3 minutes and 4 seconds | silence, tempmute, 403
unmute | Unmute a muted user. | `$unmute <user>` | None
warn | Warn a user. | `$warn <user> <reason>` | None
warnings | View warnings for a user | `$warnings <user>` | None
clearwarns | Clear a users warnings | `$clearwarns <user>` | clearwarnings
clearwarn | Clear a single warning | `$clearwarn <case id>` | clearwarning
modlogs | View moderation logs for a user | `$modlogs <user>` | None
kick | Kick a user. | `$kick <user> [<reason>]` | yeet, 409
block | Mute a user/role in the current channel. | `$block <user/role> [<reason>]` | None
unblock | Unmute a user/role who has been blocked in the current channel. | `$unblock <user/role> [<reason>]` | None
derank | Remove all roles from a user (The role must be below Fire's highest role to be removed) | `$derank <user> [<reason>]` | dethrone 

INFO COMMANDS
=================
###### The info command consists of different "subcommands", which are listed below.

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
user | Get a general overview of a user | `$info user <user>` | None
role | Get a general overview of a role | `$info role <role>` | None
guild | Get a general overview of the guild | `$info guild` | server

TAG COMMANDS
=================
###### The tag command consists of different "subcommands", which are listed below.
###### Notes: Tag names are only one word. The 'dtag' alias will delete your message when viewing a tag

Name | Description | Usage | Aliases | Permission
---- | ----------- | ----- | ------- | ----------
tag | See a list of all tags or view a tag | `$tag [<tag name>]` | dtag, tags | None
create | Create a new tag | `$tag create <name> <content>` | tags create, dtag create | Manage Messages
guild | Delete a tag | `$tag delete <name>` | tags delete, dtag delete | Manage Messages

UTILITY COMMANDS
=================

Name | Description | Usage
---- | ----------- | -----
dstatus | Get Discord's status (Made with help from [ravy](https://ravy.xyz)) | `$dstatus`
snipe | Get the last deleted message | `$snipe [<channel/user>]`
esnipe | Get the last edited message | `$esnipe [<channel/user>]`
quote | Quote a message from an id or url | `$quote <message id/message url>`
http.cat | Got a HTTP Error Code? My cat knows what it means. | `$http.cat <error code>`
membercount | Shows the amount of members | `$membercount`
avatar | Get a user's avatar | `$avatar [<user>]`
fireav | Turns your avatar info the Fire logo | `$fireav [<user>]`
tempmention | Make a role mentionable for 60 seconds or until you mention it | `$tempmention <role>`
vanityurl | Creates a vanity invite for your Discord using https://oh-my-god.wtf/ | `$vanityurl [<code>/"disable"]`
fetchchannel | Fetch a channel's info (Returns JSON) | `$fetchchannel <channel>`
fetchmsg | Fetch a message from its id or link (Returns JSON) | `$fetchmsg <message id/message url>`
fetchuser | Find a user from their id (Returns JSON) | `$fetchuser <id>`
fetchactivity | Get a member's activities (Returns JSON) | `$fetchactivity [<member>]`
tts | Make Google TTS say something! | `$tts <text>`
gassist | Talk to the Google Assistant | `$gassist <query>`

PURGE COMMAND
=================
###### The purge command uses a flags system for arguments. For example, `$purge 10 --user Geek --match oof` would purge the last 10 messages from the user Geek if it contains oof

##### Command

Name | Description | Usage
---- | ----------- | -----
purge | Bulk delete messages | `$purge <amount> [<flags>]`

##### Flags

Name | Description | Usage
---- | ----------- | -----
user | Purge messages from this user | `--user <name/mention/id>`
channel | Purge messages in this channel | `--channel <name/mention/id>`
match | Purge messages containing a string | `--match <string>`
nomatch | Purge messages that do not contain a string | `--nomatch <string>`
startswith | Purge messages starting with a string | `--startswith <string>`
endswith | Purge messages ending with a string | `--endswith <string>`
attachments | Purge messages with attachments (true = with, false = without) | `--attachments <true/false>`
bot | Purge messages from bots (true = bot, false = not bot) | `--bot <true/false>`
invite | Purge messages containing invites (true = with invites, false = without invites) | `--invite <true/false>`
text | Purge messages containing only text (true = only text, false = attachments, embeds etc.) | `--text <true/false>`

PREMIUM COMMANDS
=================
###### You can get Fire Premium by [Clicking Here](https://gaminggeek.dev/patreon) and donating

Name | Description | Usage
---- | ----------- | -----
autorole | Automatically add a role to a user when they join | `$autorole [<role name/id/mention>]` Use command without role argument to disable
addrank | Add a role that users can join through the rank command. | `$addrank <role>`
delrank | Remove a rank from the list of joinable roles. | `$delrank <role>`
rank | List all available ranks and join a rank | `$rank [<rank>]`
rolepersist | Add a role that will stay with the user, even if they leave and rejoin. | `$rolepersist <member> <role>`
antiraid | Set a channel for raid alerts. These alerts allow you to ban raiders. | `$antiraid <channel>`
raidmsg | Set a raid message. Any user who sends the message will be added to a list and send to your raid alerts channel. | `$raidmsg <message>`
