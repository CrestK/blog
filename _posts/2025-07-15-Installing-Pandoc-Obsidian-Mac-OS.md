---
layout: post
title: Installing Pandoc for Obisdian on Mac OS
subtitle: Simple, but need to put in folder path in obsidian for pandoc
tags:
  - Obisdian
  - Notes
  - Markdown
  - Pandoc
comments: false
author: Crest Koemel
---
## Steps
1. Install the pandoc plug in via the obsidian market place.
2. Install pandoc on macos enviroment

## Installing Pandoc Obsidian
Go to the Cog, or gear, I don't know the difference even after playing the create mod minecraft and loving it.
Community Plugins search Pandoc.

Install the most popular one and reboot.

## Installing Pandoc on Mac OS
Using Homebrew, run

```
brew install pandoc
```

https://pandoc.org/installing.html#macos

After it installs run
```
which pandoc

```

The output of the terminal may look something like this
```
/usr/local/bin/pandoc
```

Copy that output for later.

## Letting Pandoc Obsidian Recognize Pandoc Path
Going into your settings in obsidian, community plugins, pandoc plugin.
Scroll down to **Pandoc Path** and paste that which command output excatly as the terminal gave. 

Voila, it should be there.

Reboot and pandoc should be working.

You can type pandoc in the command platte and see all the potential commands at your finger tips.