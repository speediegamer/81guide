## https://github.com/speediegamer/the81project 
## speedie presents..
## The81Project Install Guide
## Installing Mac OS X 10.4.11 Tiger on a 2007-2008 iMac, Macbook/Air/Pro, Mac mini, Mac Pro

Documentation: ## https://github.com/speediegamer/the81project/blob/main/Documentation.pdf               

Written Guide: ## https://github.com/speediegamer/the81project/blob/main/Installation%20Guide.pdf

## https://imgur.com/a/T3YWVZE

## Pt. 1 - Introduction

First off, a little information. This guide is for the Mac users with common sense and some time to tinker. It is not that hard to follow along. It’s a noob’s guide after all. But make sure you read the full thing because there is a lot of important information that could make or break your installation experience. Please be patient when it comes to this kind of stuff. Thank you!

Also, this is a dev written guide. Through many hours of trial and error, I compiled this guide for you. Also, there is a high chance that some of your hardware won’t be supported, that’s just a fact to take in.
## Huh, is this new? I have heard that people have installed Mac OS X 10.4 Tiger on a 2008 Mac before, how is this better, or useful?
Well, people have been installing Tiger on unsupported Macs for years by cloning an install from a supported machine but this is really simplifying the process by a lot, and not only that but this is the first- time someone has made one image that can be installed on all machines. This is also the only way to see the legendary intro video as you would need to finish all updates and stuff before you can clone the drive. Also, this has a lot of third-party drivers to allow for a wider range of compatible hardware. This is also good if you don’t own an officially supported Mac. 
## TL;DR: Much easier and will work on a wider range of hardware.
## Pt. 2 - Alright, sounds good, what do I need?
The list of things needed is not that long.
* A 16GB or larger USB flash drive
* A 2008 Mac (Not DDR3 RAM)
* Patience and common sense, If you don’t know how to install an OS or plug in a USB drive, this is not the guide for you.
* Access to Windows, macOS or Linux
* balenaEtcher (For writing the image)
* Internet Connection (pretty obvious?).  

## Pt. 3 - Getting Started
Alright, so let’s go ahead and download the dmg. To do this, visit-
## https://github.com/speediegamer/the81project/releases/tag/2.0-beta
Once the web page has loaded, you will see a changelog! 

## https://imgur.com/a/GYXPRSl

Now scroll down and click the mega.nz link. Now press the big download button. Let it download. It will take a while since the file is 3.05GB in size. Once it’s finished, it’s time to download Etcher.
To do this, visit https://www.balena.io/etcher/, and then press Download for whatever your platform is.

## https://imgur.com/a/I8BLuNz

Once it’s done downloading, install etcher according to your platform.
macOS: Mount the dmg and drag the .app to the Applications folder
Windows: Run the setup and let it install.

After installing, you can proceed to the next step!

## Pt. 4 - Creating the Tiger Bootable USB

Launch Etcher, you will be greeted to a screen like this.

## https://imgur.com/a/XVRyIpF

Click “Flash from file” and then select the .dmg file we downloaded earlier. Now plug in your 16GB or larger USB flash drive. 
Make sure you have no data you care about on it because it will all be erased. Click “Select target” then click on your USB drive. Then press Select. Then press the big Flash! button and watch the magic happen!
This process could take several minutes so please be patient! Also plug the USB drive into a USB 3.0 port if possible.

## Pt. 5 - Installing The81Project.

## https://imgur.com/a/vQqWFsH

Plug your USB flash drive into one of the USB ports, depending on the device, you may need to plug it into the computer rather than a hub or a keyboard. Anyways, once done, power on the computer and hold the ⌥ Option key. Keep holding it until you see the boot picker.
Once you can see the menu, there will be a couple of options.

## https://imgur.com/a/4Ve9z1F

If you don’t have any bootable volumes except for the USB you created, there should be two volumes showing up.
Sometimes, there will be two ones named EFI Boot, you’re going to wanna pick the right one. The left one is the unmodified 10.4.11 volume. 
Most of the time though, there will be one EFI Boot and one Tiger_USB volume. If there is, select EFI Boot. Also, if you see an Apple logo then you picked the wrong volume.
If you see verbose mode then you did everything correctly. Booting to the installer shouldn’t take too long. This process should go smoothly without any issues. You can now proceed.

## Pt. 6 - Erasing your drive

If you reached the installer, good job. Now it’s time to erase the drive and install Mac OS X. 

## https://imgur.com/a/bDBn0su

Select your language, then press Continue.

Then there will be some license terms. No, these are not vanilla. They contain important information about the installation process. Be sure to read it all. Then press Continue, then Accept to accept the license terms. If your drive is empty then it should show up in the drive selection. If it doesn’t, you’ll need to erase it. Erase it as-
Mac OS Extended (Journaled) and GUID Partition Table. Once done, exit disk utility and select your volume. Then click Continue then make sure to open the Options menu. Uncheck everything available to uncheck, then press OK, now press Continue and the OS should be installing. This will take a while. You should grab a snack while it’s installing. After it’s done installing, your Mac will reboot and you can eject the USB drive from the computer.

## Pt. 7 - Post install

The little intro video will play and you can begin setting up your Mac. It is at that point you’ll find out what works and what doesn’t. Some of what doesn’t work can be fixed but a lot of it can’t. 
Set up your Mac until you reach the desktop. Now, plug in your USB drive again and open the Tiger_USB volume. There will be a package called Run After Installation.mpkg. 
Run this pkg and follow the instructions. Then select what your hardware needs. In my case, with my iMac8,1, I needed to pick TigerALC and the Airport Update in order to get everything working. 
This will be different depending on your hardware. You can also upgrade from 10.4.10 to 10.4.11. Note that if you do choose to do so, make sure to do the Airport Update or Wireless might stop working. 
It did on my system. Anyways, once this is done and your computer has restarted, you can eject your USB flash drive and enjoy your 2008 Mac running 10.4 Tiger, a sight Apple never wanted you to see. Isn’t it glorious? Well, I hoped this guide helped. Thank you for reading. 

Have a great day!

