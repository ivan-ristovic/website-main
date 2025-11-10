---
layout: page
title: The Godfather
description: A feature-rich general-purpose Discord bot
img: assets/img/projects/gf.png
github: https://github.com/ivan-ristovic/the-godfather
github_stars: false
importance: 1
category: top
---

[![Codacy Badge](https://img.shields.io/codacy/grade/9d6e1baa1ea94567a93575dc003b9b3c?style=for-the-badge)](https://app.codacy.com/gh/ivan-ristovic/the-godfather?utm_source=github.com&utm_medium=referral&utm_content=ivan-ristovic/the-godfather&utm_campaign=Badge_Grade)
[![Build Status](https://img.shields.io/appveyor/build/ivan-ristovic/the-godfather?style=for-the-badge)](https://ci.appveyor.com/project/ivan-ristovic/the-godfather)
[![Issues](https://img.shields.io/github/issues/ivan-ristovic/the-godfather?style=for-the-badge)](https://github.com/ivan-ristovic/the-godfather/issues)
[![PRs](https://img.shields.io/github/issues-pr/ivan-ristovic/the-godfather?style=for-the-badge)](https://github.com/ivan-ristovic/the-godfather/pulls)
[![Discord Server](https://img.shields.io/discord/794671727291531274?style=for-the-badge)](https://discord.gg/z7KZGQQxRz)
[![LICENCE](https://img.shields.io/github/license/ivan-ristovic/the-godfather?style=for-the-badge)](https://github.com/ivan-ristovic/the-godfather/LICENCE.md)
[![Stable release](https://img.shields.io/github/release/ivan-ristovic/the-godfather.svg?label=stable&style=for-the-badge)](https://github.com/ivan-ristovic/the-godfather/releases)
[![Latest release](https://img.shields.io/github/tag-pre/ivan-ristovic/the-godfather.svg?label=latest&style=for-the-badge)](https://github.com/ivan-ristovic/the-godfather/releases)
[![Docker URL](https://img.shields.io/docker/pulls/ivanristovic/godfather?style=for-the-badge)](https://hub.docker.com/r/ivanristovic/godfather)
[![Docker Image Size](https://img.shields.io/docker/image-size/ivanristovic/godfather?style=for-the-badge)](https://hub.docker.com/r/ivanristovic/godfather)

Just another general-purpose Discord bot developed with the goal to remove all other bots from the guild and create one that will do everything as efficiently as possible while keeping simplicity in mind when it comes to usage. Written in C# using [DSharpPlus](https://github.com/DSharpPlus/DSharpPlus).

> *Discord bots have grown very rapidly over the past few years and due to that growth it usually becomes hard to use them because of the unintuitive command system or due to performance issues. I have had a scenario where we had ten bots in the guild, because every bot did a unique job. Managing many bots and permissions for those bots quickly became overwhelming. Apart from that, only a handful of bots provided a customizable protection system against common destructive actions on Discord, yet it was still not enough - either the performance was poor due to it being a public bot instance, or the system was not customizable enough - that is if the system worked well to begin with. So, I have decided to create TheGodfather - one bot that will oversee and be in charge of everything.*
> 
> *TheGodfather became a side project for me, and it developed quite quickly. I have always intended it to be a private bot, however I realised over time that there are surely people like myself frustrated of public bot instances and dozens of narrow-purpose bots with web-based management interfaces. So, after a long time, even though this project was open sourced from the start, I decided to "open" the bot to the public - make it easier to setup and use for people who do not have programming background.*
>
> *TheGodfather is powered by the community that uses it - I do not have any financial gain from it. For that reason, the bot is meant to be self-hosted, but that might change in future if there are enough contributions from the community.*

Features:
  - Categorized and intuitive command group system with over 500 commands.
  - Complete administration of guilds, channels, users, emojis, roles, integrations etc. via categorized commands.
  - Automatic guild administration: spam protection, raid protection, mass-mention protection, ratelimit, instant join-leave protection, forbidden names and many more! All of them are customizable to suit your needs.
  - Eases your pain with auto-assignable roles, self-assignable roles, roles granted upon reaching a certain level or reacting with certain emojis.
  - A detailed history of all actions performed on users within the guild - warnings, mutes, kicks, bans. The history is queryable and editable on a per-guild basis.
  - Real-time guild backup with exemptions of specified channels.
  - Activity logs for any changes made to the guild, channels, members etc. It is possible to exempt entities (channels, users) that you do not want to be logged.
  - Message filtering either by raw string matching or regular expression matching, automatic gore websites filter, IP logging websites filter, invite filter, etc.
  - Customizable textual or emoji reactions which can be triggered by raw text or regular expression matching.
  - Customizable guild content: memes (along with meme generator), ranks, birthdays, currency, currency items and many more!
  - Searches of online services: YouTube, Wikipedia, Imgur, reddit, Steam, IMDb, OpenWeather etc.
  - RSS feed subscriptions (includes YouTube, reddit and many more) - automatic notifications when new content is released.
  - Ranking/Experience system with guild-specific rank names.
  - Many singleplayer and multiplayer games to pass your time: Quiz, Tic-Tac-Toe, Hangman, Connect4, Othello, Caro and more with stat tracking! 
  - Currency management and multiplayer gambling games: Poker, BlackJack, Slots etc.
  - Speaking of games, adventurers may wish to train their own chickens, upgrade them using guild currency, make them fight other chickens and even start ambushes or wars!
  - Todo list which can be private (via DM) or public (guild channels). Reminders can be scheduled using absolute or relative time and can be listed in various ways.
  - Music playback and queue management commands supporting YouTube, Twitch, Soundcloud and many more.
  - Starboard with customizable star emoji and reaction threshold.
  - Interactive text or reaction poll system.
  - Guild-specific culture setting (e.g. language, timezone). Currently supported languages/cultures: `en-UK` (default), `en-US`.


