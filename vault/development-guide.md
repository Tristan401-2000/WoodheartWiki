---
id: bc6cefeb-854a-47b8-8aed-f4c76c91f638
title: Development Guide
desc: 'Guide for new Woodheart developers'
updated: 1615312086250
created: 1615252255950
---

# Development Guide

This guide is intended to get new Woodheart developers setup with everything they need, as easy as possible.

## Setting up the environment

### Install Visual Studio Code <img src="https://user-images.githubusercontent.com/674621/71187801-14e60a80-2280-11ea-94c9-e56576f76baf.png" height=32>

First, you'll need to install [Visual Studio Code](https://code.visualstudio.com/). Download the Stable Build, and follow the instructions. The [Visual Studio Code Documentation](https://code.visualstudio.com/docs/) is a good resource too skim through from time to time. 

Once you have Visual Studio Code, you'll need to install a few extensions, which can be found in the extensions tab on the left side of VS Code:
- Dendron
- Dendron Markdown Links
- Dendron Markdown Preview Enhanced
- Dendron Markdown Shortcuts (optional QoL feature)
- Dendron Paste Image (optional QoL feature)
- Dendron Snippet Maker (optional QoL feature)
- Live Share
- Live Share Whiteboard
- md-graph

### Install GitKraken <img src="https://www.gitkraken.com/downloads/brand-assets/gitkraken-logo-light-hz.png" height=32>

Next, we need to install [GitKraken](https://www.gitkraken.com/). GitKraken is the desktop client we use to work with our [GitHub repository](https://github.com/Tristan401-2000/WoodheartWiki). More information about what Git is and what it's used for can be found [HERE](https://www.nobledesktop.com/blog/what-is-git-and-why-should-you-use-it).

Once GitKraken is installed, you need to "clone" the WoodheartWiki repository. This just means you will download your own local copy of the repository, and through GitKraken, you'll be able to synchronize changes back to the real repository. It's a bit more complex than that, but... baby steps.

### Clone the WoodheartWiki


To clone the repo, open GitKraken, and select "Clone a Repo". Then, in the middle column of the new dialogue box, ensure "Clone with URL" is selected. Next, pick an easily accessible location on your local drive to store the repo. The URL is below:

>https://github.com/Tristan401-2000/WoodheartWiki

> _note: you can use whatever Git client you want, but GitKraken is the default for us, and it's assumed team members are using it unless noted otherwise. On that note, GitHub Desktop is another good option, as it's the one provided BY GitHub. I think GitKraken is better though._

### Open the project in Visual Studio Code

You can either open it from Visual Studio Code itself, or from GitKraken.
- To open from VS Code, simply use ___File > Open Folder___, then navigate to where you cloned the repo to, and select the WoodheartWiki folder.
- Top open from GitKraken, open the repo in GitKraken, then use ___File > Open Repo in Visual Studio Code___.

When Visual Studio opens the WoodheartWiki folder, it should automatically start the Dendron workspace. Do not be alarmed when you can no longer see the same files and folders as before.

