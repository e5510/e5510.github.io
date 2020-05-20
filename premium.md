---
layout: article_fire
title: Fire Premium
---

# Premium

## What is Premium?

Premium is an extension to Fire that gives extra features in return for donations. These donations help me pay the bills to keep Fire up and running.

## What does Premium give you?

Premium gives you a nice set of additional features for your server

### Commands

**Autorole**

Autorole allows you to set a role that users will recieve upon joining your server

> `$autorole [<role>]` - Enable autorole, takes a role name/id/mention

\(Use the command without role argument to disable\)

**Invite Roles**

Invite roles allow you to automatically give users a role depending on what invite they used to join. You can enable/disable it with the following command

> `$invrole <invite> <role>`

\(To disable use the command again with the same invite and same role. For invite, use the code itself or discord.gg url\)
 

**Ranks**

Ranks are roles that anyone can join by typing a command. The roles users can join are from a list of roles you add.

> `$rank [<rank name>]` - List ranks or join a rank if a rank name is provided
>
> `$addrank <role>` - Add a rank that users can join \(Requires `Manage Roles`\)
>
> `$delrank <role>` - Remove a rank \(Requires `Manage Roles`\)

**Role Persist**

Role Perist allows you to give a user a role and ~~shove it down their throat~~ make sure they keep it, even if they leave and rejoin!

> `$rolepersist <member> <role>` - Give a member a role that is persistant

**Anti Raid**

Fire's anti raid features should protect your server from raids and remove the stress from moderators trying to individually ban users

> `$antiraid <channel>` - Set the channel where raid alerts will be sent
>
> `$raidmsg <message>` - Set a "raid message". Any user found saying this message in the next 5 minutes will be added to a list. After the 5 minutes, the list of users will be sent to your raid alerts channel and you can choose to ban or not using the reactions

Fire will automatically detect raids with 50 users or more. A message will be sent to your raid alerts channel where you can decide whether to ban or not.

You need to have `Ban Members` to make the decision

### Other features

**Used Invite**

See what invite a user used when they joined.

![](https://i.imgur.com/KhbwM3o.png)

If the user either 1. hasn't joined using an invite or 2. the invite is unknown, it will suggest lurking/server discovery if applicable \(Lurking requires a public guild\)

![](https://i.imgur.com/0DHdEBw.png)

**Note: Due to Discord not actually giving this information, it may not always be correct but has shown a high success rate when finding the used invite.**

**Vanity URL Stats**

With premium, you will be able to see the statistics of your server's vanity url created by Fire \(`$vanityurl`\). Stats are tracked for all servers but you need premium to view them

**Exclusive Vanity URL Domain**

Alongside the usual `oh-my-god.wtf` domain, premium users are able to use `inv.wtf` for their Vanity URLs, e.g. `https://inv.wtf/geek`

**Custom Redirects**

Using the same `inv.wtf` domain, you can create redirects to other websites, e.g. `https://inv.wtf/fire` redirecting to Fire's invite

**Priority Support**

If you're having issues with Fire and ask in the [\#help](https://canary.discordapp.com/channels/564052798044504084/564067823014641664) channel in Fire's discord, you will get faster support \(It sends a notification to my phone lmao\)

**Priority Suggestions**

Suggestions made by using the `$suggest` command will be prioritized for premium users. You can see the status of suggestions on the [Trello](https://trello.com/b/MI9bP4ZW/fire)

## Where the money goes

The money received from premium supporters goes right back to Fire via paying for the VPS every month. If there's a time when I can afford to pay for the VPS and have left over cash, it will go towards paying for things related to Fire, e.g. error tracking \([Sentry](https://sentry.io/)\), domains and anything else that will benefit Fire.

## How much is it and where do I donate?

There's currently 3 different tiers for premium. 1 server, 3 servers and 5 servers. Premium for 1 server costs $5, 3 servers costs $8 and 5 servers costs $12. Premium is purchased through my [Patreon](https://gaminggeek.dev/patreon). If you are unable to purchase premium through Patreon, please join my [Discord](https://oh-my-god.wtf/fire) and tag me \(Geek\#8405\) in the \#help channel.

This page will be updated regularly so you can be assured the information here is up to date!

