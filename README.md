# hbl2hbc
Boot from the Wii U homebrew launcher into the vWii homebrew channel, skipping controller and screen option prompts.

# Usage
1. Grab the `.zip` you want from the [releases section](https://github.com/kyoforkshomebrews/hbl2hbc/releases/latest) as described there, put it into your sd card folder.
2. If you don't want to be able to launch other Wii titles than the Open Homebrew Channel (OHBC) or launch any other titles than LULZ, OHBC and UNEO you can skip to step 4.
3. Edit `sd:/wiiu/forwarders/hbl2hbc.txt`, in the form of one or multiple lines in the format of "TitleID=TileName", to change the target channel, or create a menu of target channels.
4. Every time you want to get into the vWii open homebrew channel just start it in the Wii U homebrew launcher. 

I've included a release with my [sample hbl2hbc.txt](https://github.com/kyoforkshomebrews/hbl2hbc/blob/master/hbl2hbc.txt).
If you only want LOLZ (Homebrew Channel) download the release with the sample `.txt`, edit `hbl2hbc.txt` and remove the lines you don't need.
Also, it seems only Homebrew titles are working. I'm not sure if there's a way to launch other Wii titles,
I'm just a noob who did simple edits.

~~This works with the [Wii U Menu forwarder by brienj](https://gbatemp.net/threads/release-wiiu2hbc-a-hbl2hbc-forwarder-channel.455991/), but of course you can't press HOME to return to the hbl.~~ I plan on making a new forwarder 

If you have trouble reading this Readme, please open an issue explaining what you didn't understand!

# Credits

[FIX94](https://github.com/FIX94): Creating the initial homebrew app

[monta990](https://github.com/monta990): Changing the default Wii Channel to Open Homebrew Channel

[kyoforkshomebrews](https://github.com/kyoforkshomebrews): Changing the location of hbl2hbc.txt, changing version string, making easier to read readme, and other small additions
