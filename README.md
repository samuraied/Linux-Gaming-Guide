# Linux-Gaming-Guide
This repo is meant to be a guide for new Linux gamers from beginner to advanced.

The very first and convenient way to play games on Linux is to simply use Flatpak instead of native installs. I have read many online users spreading misleading info that Flatpak has issues, this may have been correct a long time ago, but now, it’s absolutely not true, I have been gaming on Linux for a long time (over 250 games); Mostly all run without any issues.

Step 1; Choose a Linux distro.
Every Linux distro has advantages and dis-advantages, have better communities and documentation. Choose which one works for, HOWEVER, because we are using Flatpak, there is a convenience factor, if it works in one Linux distro, 99.99% it will work in any other Linux distro on Flatpak.

Don’t fall in the trap of “This Linux distro is better than one” trap, and you should know the difference between a Linux distro and a Desktop Environment -DE-.

If you are a beginner, don’t be afraid, this is a lot easier that you imagine, especially if you know to search for information, just like any other Operating System -OS-. For example, if you don’t know how play videos on your PC or laptop, you would search for “How to play video”. Its that simple.

If you would like to save time, here is list of recommendation, you can’t go wrong with any, and there is a lot of convenience factors that I have taken into consideration.

If you are a completely new to Linux:

pop!_os : https://pop.system76.com/ 

If you are a beginner: the most convenient way is to use Fedora Workstation

![fedoramedia](https://user-images.githubusercontent.com/23434177/235343901-5ad29480-1fbb-492d-a746-5d4a12ea0833.jpg)

the official Fedora uses Gnome DE, if you click on spins, you can also use Fedora KDE DE.

![fedoramediaa](https://user-images.githubusercontent.com/23434177/235347329-af643f5d-772c-46fd-a223-91db4bc5a16b.png)

If however you want some challenge and want to learn more, there are people like that, I personally recommend Fedora Silver. You can use Fedora Media Writer to get it under Emerging Editions.
You will learn about Containers and Toolboxes and so much more.

Regardless of your choice, have fun.

Once you choose you Linux distro you can use any tool you want to write it to a USB, for convience sake, you can use Fedora Media Writer to write any Linux ISO to a USB, including Ubuntu etc…

here is your first taste of documentation, don’t get scared now : https://docs.fedoraproject.org/en-US/quick-docs/creating-and-using-a-live-installation-image/

or you can search YouTube: https://www.youtube.com/watch?v=wTsm_lDi_OU

If however you like to try a Linux distro to see if you like it or not, the most convenient way is to use Ventoy: https://www.ventoy.net/en/download.html

Now that you are ready to install Linux, look up a YouTube guide if you need it.

Now go this website : https://www.flatpak.org/setup/

After that open the terminal, copy and paste this

flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

this will enable Flathub, the best online Flatpak repo as of writing.

Now search for any app and simply copy and paste the install command.

![installcomand](https://user-images.githubusercontent.com/23434177/235344434-bb88a1b7-f084-453d-aa36-973e6e3e157c.jpg)

this for example will install Steam

flatpak install flathub com.valvesoftware.Steam

For starters here is a command you need to paste in your terminal:

flatpak install flathub com.valvesoftware.Steam net.davidotek.pupgui2 com.github.tchx84.Flatseal

This command will install Steam if you haven't installed already, and Proton-qt and Flatseal

open Flatseal and click on Steam and make sure the configuration is similar to this, notice the arrow.

![flatseal](https://user-images.githubusercontent.com/23434177/235345839-4d5b2584-4766-4be8-8ffa-57e49a988f75.png)

Note: if your internet is fast and you don’t mind downloading your games later or every time you want to try a new Linux distro, skip this step.

In this step we will install all of our games onto an external HDD or external SSD, the only difference I witnessed is loading times, other than that, there wasn’t much difference.

This will allow you to switch your Linux distro as many times as you want, and play as soon as possible.
Make sure to format your HDD/SSD to btrfs format. Look up how to do it, this will come in handy later.

Plug-in your external HDD/SSD after formatting, and create a new folder called SteamLibrary

in Steam after you log-in, click on settings → downloads → Steam Library Folders

click the (+) sign and add a new library on your hard drive.
Click the the 3 dots … and click make default.

It should look something like this

![steamlibrary](https://user-images.githubusercontent.com/23434177/235345866-12f2617f-64de-4683-9337-537ca9b8ba5d.png)

Personally I have 2 external storage devices, 1 HDD 5 teras, and 1 SSD 2 teras.

The HDD named 2-boot-y, 2Booty for short, is for games where loading times don’t matter, like Dynasty Warriors, final fantasy x/x2 and old emulators like ps1, ps2 etc….

The SSD named 2-boot-x, 2Bootx for short, is for games that do require or simply support fast loading, like Warframe and Nintendo switch emulators like Yuzu etc….

The next step is to configure Steam itself to use Proton, and GE proton.

First open Steam and go to setting – steam play and change setting look like this 
![settingssteamplay](https://user-images.githubusercontent.com/23434177/235346427-b3c72377-0dd6-4d24-bcd2-198f9b79dbe8.png)

then open Proton-qt make sure it says Steam on top, and click on Add version and choose the latest GE Proton, as of writing its 7.55
![protn](https://user-images.githubusercontent.com/23434177/235347354-bb3dad2d-2771-4a54-8f5d-fb1cade9622b.png)

Now go to any game in your Steam Library, right click and click on Properties then Compatibility
![Screenshot from 2023-04-30 12-36-12](https://user-images.githubusercontent.com/23434177/235346681-01beaa0a-042d-403e-97a4-a6ac8c81deff.png)

The rule of thump is this, use Expermental, if it does not work, or if cut-scenes don't work, use GE Proton.

What to do when a game doesn't work either way.

1st go this website https://www.protondb.com/ and search for the game, your problem might have been solved by someone else, this works for me most of time. That is not say it happenes alot, it doesn't.

2nd, if 1st fails, go this website https://github.com/ValveSoftware/Proton/issues and search the games' name here, most gamers don't have to do this, I only did this 2 times in over 4 years, and both times the problems were fixed.

Here is an example: the name of the game is WARRIORS OROCHI 3 Ultimate Definitive Edition 
https://github.com/ValveSoftware/Proton/issues/6006

![Screenshot from 2023-04-30 12-57-25](https://user-images.githubusercontent.com/23434177/235347067-9f84e567-1613-42a9-84f3-1877822cf1a5.png)

