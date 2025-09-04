# Zen Portable
A lightweight, no-install version of Zen Browser, keeping all data self-contained for portability. thus making it portable! <br>

If you follow the installation perfectly you will not encounter any weird behavior. at least on my testing, it will run normal and stable. <br>
- Common sense, basic computer knowledge, and basic problem solving skill is required. <br>
I don't want you to bother people for a solution over problem related to this repo on Zen related online forum(like Zen's Discord server or Zen's sub-reddit) and mentioning this repo. <br>

# Disclaimer
Before we continue, I need to tell you something:
1. I do not continue maintaining the Linux version, only Windows! so if you looking for Linux releases, sorry!
2. I do not responsible on any security vulnerability happening using my release. the build itself is clean from viruses.
3. I do not responsible on anything happen with your other Zen instances, for example something break your Zen profile system.

with all that said, lets continue.

## Folder Structure
```
zen-portable/
├── app/                            # files related to Zen
├── data/
│   └── profile/                    # Browser profile folder
└── launcher/
    └── zen-portable-launcher.bat   # Launcher script
```
---
## Installation and Updating
#### 1. Installation
1. Extract it anywhere on your computer.
2. run `zen-portable-launcher.bat` inside `zen-portable/launcher/` to use it.
- For easy access you can make a shortcut of the script.
- What not to do after installation is opening the browser not using the provided batch script! (it will break the Zen profile system and create another profile inside your Zen's `%localappdata%` folder that might messed up your existing installation of Zen)
#### 2. Updating
- There are multiple ways to update Zen-Portable.
- But the most stable one in my opinion would be:
1. Download the latest Zen installer (preferably through Zen Browser Github repo).
2. Run installer until the installer ask for "Custom" or "Standard" installation.
3. Choose "Custom" installation and point it toward your Zen-Portable app location `zen-portable/app`.
4. after it complete, DO NOT check "Launch Zen Now" and finish.
5. Open Zen-Portable through the script like usual.

---
## Credit
All credit goes to [**@wysh3**](https://github.com/wysh3) <br> 
Most of it was borrowed from his archived [repo](https://github.com/wysh3/Zen-Browser-Portable). <br>
All I did was just updating and continue maintaining it, I'll try to maintaining it as long as the launcher script don't break!

if i get in trouble later for stealing. <br>
please understand that i only know the basic of github, at first i plan to fork it, but i don't really know how to properly manage a forked repo. <br>
so instead i create new fresh repo. <br>
all i want is just to help people that want a portable Zen.

---
## Check out
- [tra's zen-stylesheet](https://github.com/artcens/tra-zen-stylesheet/tree/main) --- my minimal Zen ricing!
