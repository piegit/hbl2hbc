# hbl2hbc
Boot from the Wii U homebrew launcher into the vWii homebrew channel, skipping controller and screen option prompts.

# Usage
1. Grab the .zip from the downloads section, put it into your sd folder.
2. If you don't want to be able to launch other Wii titles than the Open Homebrew Channel (OHBC) you can remove the file sd:/wiiu/apps/hbl2hbc/hbl2hbc.txt from the sd card of your Wii U and skip to step 4.
3. Edit sd:/wiiu/apps/hbl2hbc/hbl2hbc.txt, in the form of one or multiple lines in the format of "TitleID=TileName", to change the target channel, or create a menu of target channels.
4. Every time you want to get into the vWii open homebrew channel just start it in the Wii U homebrew launcher. 

I've included a sample hbl2hbc.txt in the release. If you only want to launch OHBC (Open Homebrew Channel), delete it. If you only want LOLZ (Homebrew Channel), edit
hbl2hbc.txt and remove the lines you don't need. Also, it seems only Homebrew titles are working. I'm not sure if there's a way to launch other Wii titles,
I'm just a noob who did simple edits.

# Credits

[Fix49](https://github.com/FIX94): Creating the initial homebrew app.

[monta990](https://github.com/monta990): Changing the default Wii Channel to Open Homebrew Channel

[kyoforkshomebrews (myself)](https://github.com/kyoforkshomebrews): Changing the location of hbl2hbc.txt, changing version string, making easier to read readme, etc.. 
