---
layout: article
title: Fire - Commands List
mode: default
header:
  theme: dark
article_header:
  type: overlay
  theme: dark
  background_color: '#FF5A00'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(255,83,0,0.4), rgba(255,147,0,0.4))'
    src: /assets/firecover.png
---

##### All of these examples use the default prefix, `$`

MAIN COMMANDS
==============

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
ping | Shows you my ping to discord's servers | `$ping` | None
suggest | Suggest a feature | `$suggest <suggestion>` | None
stats | Shows you some stats about me | `$stats` | None
rpc | View someone's rich presence | `$rpc [<member>]` | None
dab | dab. | `$dab` | None
warm | warm something up | `$warm <something>` | None
cowsay | Cow goes moo (or whatever really) | `$cowsay <text>` | None
ascii | Make ASCII text | `$ascii <text>` | None
👏 | Emphasise your text with clapping | `$clap <text>` | clap

HYPIXEL
==============
###### The Hypixel command consists of different "subcommands", which are listed below.

Name | Description | Usage
---- | ----------- | -----
key | See my API key usage | `$hypixel key`
watchdog | See watchdog stats, usually broadcasted every 2 hours on the server | `$hypixel watchdog` 
player | Get a general overview of a player | `$hypixel <player>`
guild | Get a general overview of a player's guild & members | `$hypixel <player> guild`
friends | Get a general overview of a player's friends | `$hypixel <player> friends`

KSoft.Si COMMANDS
=================

Name | Description | Usage | Requirements
---- | ----------- | ----- | ------------
meme | Get a random meme | `$meme [<subreddit>]` | None
image | Get an image from a tag | `$image <tag>` | None
imagetags | Get a list of tags (for the above command) | `$imagetags` | None
baninfo | Get info about a ban on KSoft.Si | `$baninfo <user id>` | Be in the [KSoft.Si Discord](https://discord.gg/kEf6qXN)

SK1ER COMMANDS
=================

Name | Description | Usage
---- | ----------- | -----
levelhead | Get a player's levelhead info | `$levelhead <player>`

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
###### UPDATE: As of 10th October 2019, this command has been disabled temporarily. There's no ETA for it's return

Name | Description | Usage
---- | ----------- | -----
yt | Get the top 5 trending videos in the US | `$yt`
yt info | Get a video's info from an ID or URL | `$yt info <id|url>`

MUSIC COMMANDS
=================

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
connect | Connect to a voice channel | `$connect <channel>` | join
play | Queue a song or playlist for playback. | `$play <search query|url>` | sing, p
np | Sends the music controller message which contains various information about the current and upcoming songs. | `$np` | now_playing, current, currentsong
pause | Pause the currently playing song. | `$pause` | None
resume | Resume a currently paused song. | `$resume` | None
skip | Skip the current song. | `$skip` | None
stop | Stop the player, disconnect and clear the queue. | `$stop` | None
volume | Change the player volume. | `$volume <number: 1-100>` | vol
queue | Retrieve a list of currently queued songs. | `$queue` | q, que
shuffle | Shuffle the current queue. | `$shuffle` | mix
repeat | Repeat the currently playing song. | `$repeat` | None
seteq | Pick from one of the equalizer presets to change your music. | `$seteq <Flat|Boost|Metal|Piano>` | None

SETTINGS COMMANDS
=================

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
settings | Run through my setup process to configure a few settings | `$settings` | setup
setlogs | Set a channel for logging | `$setlogs <channel>` | None

MODERATION COMMANDS
=================
###### Users with the `Manage Messages` permission are considered moderators and can use these commands. Be careful who you give this permission to

Name | Description | Usage | Aliases
---- | ----------- | ----- | -------
ban | Ban a user from the server | `$ban <user> [<reason>]` | banish
unban | Unban a user from the server | `$unban <user> [<reason>]` | unbanish
softban | Bans a user, deletes messages from a specified amount of days and then unbans. | `$softban <user> <amount of days: 1-7> [<reason>]` | None
mute | Mute a user. | `$mute <user> [<time> <reason>]` Time format: 1d 2h 3m 4s == 1 day, 2 hours, 3 minutes and 4 seconds | silence, tempmute
unmute | Unmute a muted user. | `$unmute <user>` | None
warn | Warn a user. | `$warn <user> <reason>` | None
warnings | View warnings for a user | `$warnings <user>` | None
clearwarns | Clear a users warnings | `$clearwarns <user>` | clearwarnings
clearwarn | Clear a single warning | `$clearwarn <case id>` | clearwarning
modlogs | View moderation logs for a user | `$modlogs <user>` | None
kick | Kick a user. | `$kick <user> [<reason>]` | None
block | Mute a user in the current channel. | `$block <user> [<reason>]` | None
unblock | Unmute a user who has been blocked in the current channel. | `$unblock <user> [<reason>]` | None

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
purge | Bulk delete messages | `$purge <amount> [<user>]`
snipe | Get the last deleted message | `$snipe [<channel|user>]`
esnipe | Get the last edited message | `$esnipe [<channel|user>]`
quote | Quote a message from an id or url | `$quote <message id|message url>`
http.cat | Got a HTTP Error Code? My cat knows what it means. | `$http.cat <error code>`
avatar | Get a user's avatar | `$avatar [<user>]`
fireav | Turns your avatar info the Fire logo | `$fireav [<user>]`
tempmention | Make a role mentionable for 60 seconds or until you mention it | `$tempmention <role>`
vanityurl | Creates a vanity invite for your Discord using https://oh-my-god.wtf/ | `$vanityurl [<code>|"disable"]`
fetchchannel | Fetch a channel's info (Returns JSON) | `$fetchchannel <channel>`
fetchmsg | Fetch a message from its id or link (Returns JSON) | `$fetchmsg <message id|message url>`
fetchuser | Find a user from their id (Returns JSON) | `$fetchuser <id>`
fetchactivity | Get a member's activities (Returns JSON) | `$fetchactivity [<member>]`
tts | Make Google TTS say something! | `$tts <text>`
gassist | Talk to the Google Assistant | `$gassist <query>`

PREMIUM COMMANDS
=================
###### You can get Fire Premium by [Clicking Here](https://gaminggeek.dev/patreon) and donating

Name | Description | Usage
---- | ----------- | -----
autorole | Automatically add a role to a user when they join | `$autorole [<role name/id/mention>]` Use command without role argument to disable
reactrole | Automatically add a role to a user when they react to a message | `$autorole [<role name/id/mention> <message id> <emote>]` Use command without arguments to disable
addrank | Add a role that users can join through the rank command. | `$addrank <role>`
delrank | Remove a rank from the list of joinable roles. | `$delrank <role>`
rank | List all available ranks and join a rank | `$rank [<rank>]`
rolepersist | Add a role that will stay with the user, even if they leave and rejoin. | `$rolepersist <member> <role>`
