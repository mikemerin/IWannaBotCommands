### I Wanna Bot mIRC Commands

This is a repo to store the IWannaBot Commands used for Twitch's Fangame Marathon.

These commands are written in MSL (mIRC Scripting Language) and stored in a **remote.ini** file.

This corresponds to the primary file in this repo: **remote.msl**. Other scripts for other channels / testing / unused are in the **other* folder.

While you cannot copy/paste the commands directly into the file (see location below) you can paste the commands by doing the following:

1. Open up mIRC
1. Click on the "Scripts Editor" button (5th from the left)
1. Click on the "Remote" tab
1. Paste Here
1. Click "OK" to save and reload

For reference, the location where **remote.ini** is located is **C:\Users\Mike\AppData\Roaming\mIRC\scripts**

### Commands

#### User commands
* !commands (List all user commands, which are as follows)
* !discord (Discord invite link)
* !intro (Link to https://fangam.es/intro)
* !fangame (Link to https://fangam.es)
* !jumps (Link to jump image http://puu.sh/k8lSk/4678139789.png)
* !game (Current game’s info (if it’s active, not before/after/in between games))
* !schedule (Link to https://horaro.org/fm/2021, also lists the current run info)
* !next (Next run and runner info)

#### Admin commands
* !update [previous | current | next]
  * Updates the !ffzfollow information

#### Superadmin commands (ShadowsDieAway and FangameMarathon only)
* !repeat_on
* !repeat_follow
* !repeat_discord
* !repeat_intro
* !repeat_fangame
* !repeat_off (Turns off all repeated commands (usually for the end of the marathon))
* !a_delete (Deletes all registered admins to the bot)
* !a_create (Sets ShadowsDieAway, FangameMarathon, Wolsk, and Denferok as main admins registered to the bot)
* !a_check (Tests if a user is a registered admin to the bot)
