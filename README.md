###### Public repository for the [irc.chew.pro](https://irc.chew.pro) IRC network.

---
description: Channels, rules, guides, and more!
---

# Network Staff

Here is a list of staff.

 Chew - Global NetAdmin

mueslivines - NetAdmin

Cah - irc.cahbot.pro NetAdmin

Saorn - Global Helper


# Custom Hostmask

| Table of Contents
| ---------------------------------------------------------------------------------------------------------------
| 1. [Introduction](#introduction)<br>2\. [Server Hostmask](#server-hostmask)<br>3\. [Custom Hostmask](#custom-hostmask)<br>4\. [Extra Info](#extra-info)

## Introduction

Requirement:
[You MUST be identified with NickServ](http://chewcraft.github.io/IRC/help/registernickserv#Authenticating-on-Login)!

Let’s get a hostmask.

You can either use a hostmask provided by the server, or request your own custom one.

### Server Hostmask

It’s simple! Type `/hs offerlist`.

You now have a list of available offers. The bot will guide you on how to take a vhost, and to enable it type `/hs on`

You’re done!

### Custom Hostmask

To request a hostmask, you must do something similar.

Type `/hs request [your hostmask]`

Rules for hostmasks:
No spaces or other special characters (emojis for example), dots are allowed.

## Extra Info

We will process your request in a reasonable amount of time, bugging us will lower your priority.


# Register with NickServ

| Table of Contents
| ---------------------------------------------------------------------------------------------------------------
| 1\. [Registering](#registering)<br>2\. [Authenticating on Login](#authenticating-on-login)<br>3\. [BONUS: Auto-authenticating with IRCCloud](#bonus-auto-authenticating-with-irccloud)

## Registering

Registering is simple! Simply type `/msg NickServ REGISTER [password] [email]`

TIP: Our server also allows `/ns` as an alias of `/msg NickServ`!

Example:

![A picture showing a successful registration](https://user-images.githubusercontent.com/8278263/31468518-af35718c-aea3-11e7-86e9-fed88a7f91eb.png)

## Authenticating on Login

This step isn't too difficult. Simply type `/msg NickServ IDENTIFY [password]`! Simple!

NOTE: You can authenticate using a different nick (example: You registered as `nickservisgreat` and you want to log in as `chanservisscarry`) type `/msg NickServ IDENTIFY [register nick] [its password]`

![A picture showing successful login](https://user-images.githubusercontent.com/8278263/31468637-398ffdfc-aea4-11e7-9029-71086365b96c.png)

## BONUS: Auto-authenticating with IRCCloud.

Lazy? Use IRCCloud? You can authenticate with NickServ automatically!

*Assuming you're using Desktop or Website*

Head to the channel list and hover over the server name, and click this gear.

![Head to the channel list and hover over the server name, and click this gear](https://user-images.githubusercontent.com/8278263/31468713-95d102c8-aea4-11e7-9255-a9d2e9996676.png)

Click Identify Nickname on the dropdown menu.

![the dropdown menu](https://user-images.githubusercontent.com/8278263/31468730-a849334e-aea4-11e7-8214-dca5e839b01b.png)

This box will appear, type in your password and click "Set password and identify"

![that box](https://user-images.githubusercontent.com/8278263/31468759-cab486e0-aea4-11e7-9f49-2d2ec72406ee.png)

IRCCloud's so nice, it even gives you how to register! No tutorial needed!


# Add your channel

To add your channel, you must either PM Chew or send a PR with the following info.

1) The Channel Name.

2) A channel description.

3) Any specific rules.

4) Channel Staff (and their roles)

A staff will join on official network business if they aren't already there. They will leave once they get the rest of the information needed.


# Example Skeleton Format

If you decide to PR yourself, follow this format. Replace []s with your input. Otherwise, add no modifications.

Not viewing properly? Click [here](http://github.com/ChewCraft/IRC/blob/master/info/addchannel.md).

```markdown
# #[channel name]

Status: User Owned Channels

Founder: [your nickname]

<!-- Add your channel info here -->

## Description

[Add a description, if none, say "No description"]

## Rules

[Chanel specific rules?]

## Channel Staff

- [you] (Owner)
- [other staff] [their rank]

## Channel Bots

- [bot name]
```

# Modifying your channel info

This is really simple to do! Just modify the file in your fork, send a PR, and after review will be modified!

If you want to delete a channel, just delete the file and PR that change.


# Join The Network

You can join the network via KiwiIRC or IRCCloud (web clients) or your own choice of desktop/mobile client. We recommend IRCCloud as your client because of its mobile apps and always connected feature.

IP: `irc.chew.pro` or `irc.cahbot.pro`<br>
Port: 6667<br>
No SSL...

[KiwiIRC Link](http://chewcraft.github.io/IRC/webchat) - No Sign-Up, Connection Closes on tab close

[IRCCloud Link](https://www.irccloud.com/invite?channel=%23lobby&hostname=irc.chew.pro&port=6667) - Sign-Up AND Email Verification Needed. Won't close connection when tab closes.


# Official Network Rules

By joining the server, you agree to following these very simple rules.

1) Your channel rules MUST INCLUDE THESE RULES unless it meets the requirements to bypass the rule.

2) Absolutely NO NSFW. (Exception [channels only]: Mode MUST BE +s AND +i or +k, and must contain NSFW in the channel name.)

3) Advertising other irc networks are prohibited. Anywhere.

4) Spamming (or pinging) any network staff for any reason is strictly prohibited unless they specifically allow it in a channel.

