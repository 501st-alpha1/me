# About Me
This is a landing page for my GitHub profile, to help you navigate my repos.  If you are overwhelmed by the dozens of [repositories listed on my profile](https://github.com/501st-alpha1?tab=repositories), you are in the right place.  I'll also link here when applying for jobs, so that recruiters / hiring managers don't have to go digging through my profile to find useful information about how I write code and communicate on projects.

# Repos

## My Projects
These are open source projects that I have started, with the intent to be used more widely (though some may still be incomplete).

| Name / Link | Description |
|-------------|-------------|
| [Big Gollum](https://github.com/501st-alpha1/big-gollum) | A rails app that lets you make, browse, edit, and eventually control permission to gollum wikis.  Created by [@oponder](https://github.com/oponder/), I became co-maintainer after helping develop it, and later the project was given to me. |
| [Codeception Data Selector](https://github.com/501st-alpha1/codeception-data-selector) | A Codeception extension to automatically select data from DB based on certain conditions. |
| [Emacs Org EBS](https://github.com/501st-alpha1/emacs-org-ebs) | An Emacs Org-Mode implementation of Joel Spolsky's Evidence-Based Scheduling. |
| [sqrl-qt](https://github.com/sqrl-qt/sqrl-qt) | Beginning of project to implement a desktop client for [SQRL](https://sqrl.grc.com/).  No recent activity due to lack of time, and other higher priorities, but may come back to eventually. |
| [XP to Emerald Plugin](https://github.com/501st-alpha1/XP-to-Emerald-Plugin) | Plugin for the Bukkit Minecraft server to allow users to convert XP to Emeralds and back again.  Not updated recently for same reasons as above.  Original commit in 2012 (!), and it needs some major refactoring, but It Works! :tm: |

TODO: Add repos.

## Examples and Interview Projects
These are projects that were written either for fun or as part of an interview, and are published here to give examples of how I write and manage code.

| Name / Link | Description |
|-------------|-------------|
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

### Other

TODO: Add repos.

## To Sort

- https://github.com/501st-alpha1/blog
- https://github.com/501st-alpha1/Java-Chess-App
- https://github.com/501st-alpha1/facebook
- https://github.com/501st-alpha1/ultimate-compile.el
- https://github.com/501st-alpha1/nasb-mode
- https://github.com/501st-alpha1/Commercial-Standard-License
- https://github.com/501st-alpha1/emacs-auto-formatter
- https://github.com/501st-alpha1/crypto-signatures
- https://github.com/501st-alpha1/dwolla.net-v2
- https://github.com/501st-alpha1/bento4-cli-nuget
- https://github.com/501st-alpha1/ef-auto-soft-delete
- https://github.com/501st-alpha1/cross-platform-php-docker-image
- https://github.com/501st-alpha1/cross-platform-node-docker-image
- https://github.com/501st-alpha1/laravel-mvp
- https://github.com/501st-alpha1/ledger-autobot
- https://github.com/501st-alpha1/cross-platform-docker-images
- https://github.com/501st-alpha1/docker-ngircd
- https://github.com/501st-alpha1/floss-weekly

# Contributing
If you see a missing repo, feel free to [open an issue](https://github.com/501st-alpha1/me/issues/new), or if you can guess where the repo should be, [open a pull request](https://github.com/501st-alpha1/me/pulls/new).
