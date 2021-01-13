# About Me
This is a landing page for my GitHub profile, to help you navigate my repos.  If you are overwhelmed by the dozens of [repositories listed on my profile](https://github.com/501st-alpha1?tab=repositories), you are in the right place.  I'll also link here when applying for jobs, so that recruiters / hiring managers don't have to go digging through my profile to find useful information about how I write code and communicate on projects.

I intend for this page to be comprehensive, so if you are looking for some repo in particular, a search for the repo name should bring you to the right place.

# Repos

## My Projects
These are open source projects that I have started, with the intent to be used more widely (though some may still be incomplete).

| Name / Link | Description |
|-------------|-------------|
| [Big Gollum](https://github.com/501st-alpha1/big-gollum) | A rails app that lets you make, browse, edit, and eventually control permission to gollum wikis.  Created by [@oponder](https://github.com/oponder/), I became co-maintainer after helping develop it, and later the project was given to me. |
| [Codeception Data Selector](https://github.com/501st-alpha1/codeception-data-selector) | A Codeception extension to automatically select data from DB based on certain conditions. |
| [Emacs Auto Formatter](https://github.com/501st-alpha1/emacs-auto-formatter) | An Emacs plugin to automatically format code according to user preferences.  Still WIP. |
| [Emacs Org EBS](https://github.com/501st-alpha1/emacs-org-ebs) | An Emacs Org-Mode implementation of Joel Spolsky's Evidence-Based Scheduling. |
| [Git Kraken Boards Exporter](https://github.com/501st-alpha1/git-kraken-boards-exporter) | A Python script to export data from GitKraken Glo Boards using their API. |
| [git-rstash](https://github.com/501st-alpha1/git-rstash) | A simple Git extension to transfer stashes to and from remote repositories. |
| [ledger-autobot](https://github.com/501st-alpha1/ledger-autobot) | A bot to automatically run [ledger-autosync](https://github.com/egh/ledger-autosync) and submit a Pull Request with the result.  Currently delaying work on this until I can automate the download of OFX files from banks that don't support OFX Direct Connect. |
| [sqrl-qt](https://github.com/sqrl-qt/sqrl-qt) | Beginning of project to implement a desktop client for [SQRL](https://sqrl.grc.com/).  No recent activity due to lack of time, and other higher priorities, but may come back to eventually. |
| [XP to Emerald Plugin](https://github.com/501st-alpha1/XP-to-Emerald-Plugin) | Plugin for the Bukkit Minecraft server to allow users to convert XP to Emeralds and back again.  Not updated recently for same reasons as above.  Original commit in 2012 (!), and it needs some major refactoring, but It Works! :tm: |

### Distribution of 3rd Party Code

These repos were for the most part not developed by me, but I packaged up existing code to make it easier to distribute for my needs.

- https://github.com/501st-alpha1/bento4-cli-nuget
- https://github.com/501st-alpha1/ef-auto-soft-delete
- https://github.com/501st-alpha1/facebook
- https://github.com/501st-alpha1/cross-platform-docker-images
- https://github.com/501st-alpha1/cross-platform-php-docker-image

### Misc

- https://github.com/501st-alpha1/Commercial-Standard-License
- https://github.com/501st-alpha1/crypto-signatures
- https://github.com/501st-alpha1/floss-weekly
- https://github.com/501st-alpha1/referrals

### Placeholders

These projects are not very far along in their development, and are mainly here as placeholders for things I want to do in the future.

- [Blog Posts](https://github.com/501st-alpha1/blog)
- [Emacs Mode for reading the NASB](https://github.com/501st-alpha1/nasb-mode)
- [Compiling code in Emacs](https://github.com/501st-alpha1/ultimate-compile.el)
- [Web app Minimum Viable Product in Laravel](https://github.com/501st-alpha1/laravel-mvp)
- [.NET library for v2 of Dwolla's API](https://github.com/501st-alpha1/dwolla.net-v2)
- [Docker image for ngircd server](https://github.com/501st-alpha1/docker-ngircd)

## Examples and Interview Projects
These are projects that were written either for fun or as part of an interview, and are published here to give examples of how I write and manage code.

| Name / Link | Description |
|-------------|-------------|
| [Java Chess App](https://github.com/501st-alpha1/Java-Chess-App) | Example project I created in Java while still in school.  Not updated much since then. |
| [rpn-calculator](https://github.com/501st-alpha1/rpn-calculator) | A command-line Reverse Polish Notation (RPN) calculator, written as part of the On-Site interview process. |

## Personal Configs
These are personal config files and scripts for various programs.  While I publish them here on GitHub, I don't expect them to be used widely (though I have no problem if they are).  The more likely use is someone may be looking for a solution to a specific problem and find it in one of these repos.

| Name / Link | Description |
|-------------|-------------|
| [emacs-init](https://github.com/501st-alpha1/emacs-init) | Public portion of my configuration for Emacs. |
| [git-template](https://github.com/501st-alpha1/git-template) | Template for new `.git` folders. |
| [i3wm-config](https://github.com/501st-alpha1/i3wm-config) | My config for the [i3 window manager](//i3wm.org) |
| [scott-script](https://github.com/501st-alpha1/scott-script) | Various Bash scripts that I use.  Some of them may be useful for wider audiences, but those should probably be extracted to separate repos eventually. |
| [scott-server-scripts](https://github.com/501st-alpha1/scott-server-scripts) | Same as above but for scripts that I only need on servers. |

## Third Party Projects (Forks)
Below are some selected contributions to third party projects.  Most forks are made with the intent to submit PRs against upstream, but I'll note here if they have any other uses.

### ledger-autosync

<dl>
  <dt>Source</dt>
  <dd>https://github.com/egh/ledger-autosync</dd>
  
  <dt>Fork</dt>
  <dd>https://github.com/501st-alpha1/ledger-autosync</dd>
  
  <dt>Source Description</dt>
  <dd>Synchronize your ledger-cli files with your bank.</dd>
</dl>

From the README:

> ledger-autosync is a program to pull down transactions from your bank and create [ledger](http://ledger-cli.org/) transactions for them. It is designed to only create transactions that are not already present in your ledger files (that is, it will deduplicate transactions). This should make it comparable to some of the automated synchronization features available in products like GnuCash, Mint, etc. In fact, ledger-autosync performs OFX import and synchronization better than all the alternatives I have seen.

My contributions:

- [Match autosync payee](https://github.com/egh/ledger-autosync/pull/62)

  New feature to allow renaming payees to a more reasonable value in Ledger files, but still match with what bank says they are.  Discussed design of feature prior to implementation, in [issue #25](https://github.com/egh/ledger-autosync/issues/25).  Also added automated test for new functionality.
  
- [Get adjusted memo](https://github.com/egh/ledger-autosync/pull/80)

  Follow-up to above PR, allowing matching to be applied to `MEMO` OFX field if bank uses that instead of `NAME`.  Again discussed design prior in [issue #71](https://github.com/egh/ledger-autosync/issues/71).

- [Add argument to specify ofxclient config file](https://github.com/egh/ledger-autosync/pull/58)

  Small change to allow specifying which config file to use, so I didn't have to edit the hardcoded path of `$HOME/ofxclient.ini` every time.
  
- Opened various other issues that I didn't implement solutions for myself (at least, not yet); see [here](https://github.com/egh/ledger-autosync/issues?utf8=%E2%9C%93&q=is%3Aissue+author%3A501st-alpha1).

### ledgercalc

<dl>
  <dt>Source</dt>
  <dd>https://github.com/artisancomputer/ledgercalc</dd>
  
  <dt>Fork</dt>
  <dd>https://github.com/501st-alpha1/ledgercalc</dd>
  
  <dt>Source Description</dt>
  <dd>multifunction + variables RPN calculator for ledger </dd>
</dl>

`ledgercalc` is a Python script to perform simple calculations on [Ledger](https://www.ledger-cli.org/) balances.

My contributions:

- [Allow filtering transactions by payee](https://github.com/artisancomputer/ledgercalc/pull/1)

  Added ability to filter transactions included in balance by payee, rather than only using raw account balance.  Discussed improvments in PR comments; now waiting on owner to merge.

<!--

### REPO

<dl>
  <dt>Source</dt>
  <dd>LINK</dd>
  
  <dt>Fork</dt>
  <dd>https://github.com/501st-alpha1/REPO</dd>
  
  <dt>Source Description</dt>
  <dd>DESC</dd>
</dl>

From the README:

DESC

My contributions:

- [TITLE](PR)

  DESC

-->

### Formatting, typos, and misc small fixes

Because [no pull request is too small!](https://adamralph.com/2015/10/12/no-pull-request-is-too-small/)

- https://github.com/egh/ledger-autosync/pull/82
- https://github.com/egh/ledger-autosync/pull/81
- https://github.com/MicrosoftDocs/azure-docs/pull/294
- https://github.com/BabylonJS/Babylon.js/pull/1138
- https://github.com/Codeception/Specify/pull/21
- https://github.com/editorconfig/editorconfig-emacs/pull/48
- https://github.com/d4be4st/progress_job/pull/7
- https://github.com/anlutro/laravel-4-smart-errors/pull/27
- https://github.com/gollum/rugged_adapter/pull/8
- https://github.com/bbatsov/projectile/pull/677

### Other

TODO: Add repos.

<!--

Last updated info:

PRs checked through: 2020-06-24
Source repos checked through: ~2019-06-20
Forks checked through: Unknown

-->

# Contributing
If you see a missing repo, feel free to [open an issue](https://github.com/501st-alpha1/me/issues/new), or if you can guess where the repo should be, [open a pull request](https://github.com/501st-alpha1/me/pulls/new).
