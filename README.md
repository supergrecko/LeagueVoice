# League Voice

Manage champion select with the power of your voice!

![League Voice](/web/static/app.png)

---

## Installation

For regular users, head over to the [releases](https://github.com/supergrecko/LeagueVoice/releases) tab and download the win32.zip file. This file contains everything you need to run League Voice.

For developers, clone this repository using git and run these commands.

```bash
$ npm install
$ npm rebuild --runtime=electron --target=3.0.0 --dist-url=https://atom.io/download/electron
```

#### Requirements

The requirements to use League Voice are listed here.

- Windows 64-bit Operating System
- League of Legends Client & account
- Google account

#### Releases

The releases can be found [here](https://github.com/supergrecko/LeagueVoice/releases). League Voice follows the [semver](//semver.org) standard.

## Overview

#### Table of Contents

- [What is League Voice](#what-is-league-voice)
- [How do I use League Voice](#how-do-i-use-league-voice)
    - [Linking accounts](#linking-accounts)
    - [Making commands](#making-commands)
- [Command List](#command-list)
- [Troubleshooting](#troubleshooting)
    - [Common Issues](#common-issues)
    - [Still having issues?](#still-having-issues)
- [Legal](#legal)
    - [Data Policies](#data-policies)
    - [License](#license)
    - [Riot Note](#riot-games)

#### What is League Voice?

League Voice is an application to connect your League of Legends champion select to your Google Assistant.

We create a real-time connection between the League Client and the Google Assistant. Every time you tell the assistant to do something, we let the League Client know what to do.

#### How do I use League Voice?

First you need to add the League Voice app to your Google account. This can be done by following [this three-step guide by Google](https://support.google.com/googlehome/answer/7126338)

To use League Voice you need to link your League account to a Google account. This can be done by pressing the "Link" button and asking your Google Assistant to link your accounts.

A more detailed explanation about the linking process can be found [here](#Linking-accounts)

---

When you've linked your accounts you'll be able to use League Voice. Simply enter champion select and tell your assistant to do some actions. 

A more detailed explanation about using the assistant can be found [here](#Making-commands)

###### Linking accounts

The linking of accounts is a three-step procedure. 

1. Request your assistant to begin linking your accounts.
1. Click the "Link" button on the League Voice app.
1. Tell your assistant the generated phrase that appears on-screen.

###### Making commands

#### Command List

The amount of Client support for the League Assistant is currently limited (due to this being a submission for the Riot API challenge). It currently only supports very basic features. If you have any requests for future ideas, please submit an issue with your feature request and we will review it.

- [Pick a champion]
- [Ban a champion]
- [Change summoner spells]

#### Troubleshooting

###### Common Issues

> Doesn't pick or ban my intended champion

The application needs to be running (you can start the app by clicking the "Start" button). 

Your League accounts needs to be linked with a Google Account. This procedure can be started by clicking the "Link" button and telling your Google Assistant to link your accounts.

If your intended champion has been picked or banned the assistant will not perform any action and you will need to request it to pick/ban another champion.

> Doesn't start upon pressing start

If you recently restarted your League Client make sure to restart your League Voice application as well.

###### Still having issues?

If your issue is not addressed in the Common Issues article and if you can't resolve any of the error messages you can report this error by submitting an issue.

Before sending your issue, make sure it has not already been addressed in the issues list. You can check the issues [here](https://github.com/supergrecko/LeagueVoice/issues) 

## Legal

#### Data Policies

League Voice stores certain pieces of data to make the application function.

By using League Voice you agree to allowing us to store these pieces of information.

- League of Legends Summoner Name
- League of Legends PUUID (An internal ID)
- Google Account ID

We use this data to link your Google account with your League of Legends account. This data is not shared with any third-party.

We need to collect this data to authenticate you so the client receives the correct data. This also prevents other users from interacting with your client.

#### License

This project is licensed under the MIT License. A copy of the license can be found in the root directory of this package.

#### Riot Games

League Voice was created under Riot Games' "Legal Jibber Jabber" policy using assets owned by Riot Games.  Riot Games does not endorse or sponsor this project.