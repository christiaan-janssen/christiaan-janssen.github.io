---
author: shidima
categories:
- Uncategorized
date: 2015-04-05T05:46:13Z
guid: http://drunkturtle.com/?p=21
id: 21
title: Asus T100 and Linux
url: /2015/04/05/asus-t100-and-linux/
---

For some time now I own a Asus T100 Laptop. It's a nice and small machine running Windows 8. After having used it for a couple of months with Windows 8 (and 8.1) it works good. I don't have a lot of problems with the Metro interface, as it still supports my workflow without any problems. I honestly think that this is the longest I have had a device running it's stock software since my Windows XP machine.
<h4>Time for change!</h4>
As I'm a big fan of Linux, I always look for a way to install it on my devices. So I have been looking for a way to install it on my T100. Unfortunately, the new Bay Trail chip set in my T100 was lacking in Linux support on launch. In part due to the fact that its actually a tablet and not a laptop, and the layout of the hardware is different than that of a <em>normal</em> laptop.

For a while now I have been following the developments in the <a href="https://plus.google.com/communities/117853703024346186936">Ubuntu camp</a>, and it is looking very good. The creation of the installation medium is still a bit of a hassle. But after having re-installed my main PC with Fedora 21, I started looking in that direction for my T100 also.
<h4>Enter Fedlet</h4>
<a href="https://www.happyassassin.net/fedlet-a-fedora-remix-for-bay-trail-tablets/">Fedlet</a> is a Fedora remix aimed at Bay Trail platforms. It was originally designed for the Dell Venue Pro 9, but it is getting more support for the T100 (Or other Bay Trail hardware). The installation instructions in particular were much more simple than what I found for Ubuntu, so I gave it a spin.
<h4>Ready?</h4>
Making the medium was just a case of dd'ing the file to a USB stick. Installing it, was a different beast. First you need to disable secure boot to allow booting from USB. The USB live install booted with out much problems, the problems for me where with the install, it kept crashing or it got stuck at 100%. After trying some different options I found a combination to install it to my hard drive.
<pre>anaconda –liveinst –method=livecd:///dev/mapper/live-base</pre>
After the install the boot was stuck at running systemd start jobs. It was a bit hit and miss on boot, very 3th or 4th boot I would get into the system.

Once booted almost every thing seemed to be working, WiFi, touch screen (Sometimes only left click) sound and keyboard special keys. The hardware sound buttons were not working, but that's something I don't expect will work without help from Asus.

Unfortunately the system is far from stable, it has random freezes and updating it also makes it get stuck. And that in turn makes the system more unstable.
<h4>Conclusion</h4>
While I would love to run Linux on my T100, it's still much to unstable to run on a day to day base. There are a lot of patches coming, but until all the hardware runs the way it shuld I'm sticking with windows (Windows 10 to be more precise).