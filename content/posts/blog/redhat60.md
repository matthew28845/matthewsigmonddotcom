---
title: "Period Correct 1999 Red Hat Linux 6.0 Installation"
date: 2024-12-22T21:45:05-05:00
draft: false
params:
  author: Matt Sigmond
---

![ThinkPad shots](/posts/blog/images/redhat60/IMG_1765.JPEG)

I've had this IBM ThinkPad 385XD for a few years now. I paid only $30 for it from somebody who was about to take it to a recycler, but had mercifully decided to first post it on Craigslist in case anybody wanted it. It's hard to see in photos, but it's in nearly perfect condition. The only flaw on the machine is a scratch on the lid between the hinge and the status indicator lights, which I added and will regret doing for the rest of my life. I'll put more photos of it at the bottom. For now though, its basic specs are a 233MHz Pentium MMX CPU, 32MB of RAM, a 3.2GB hard drive, and an 800x600 active-matrix LCD display. This ThinkPad would have been a midrange model when it was new, with thinkwiki.org describing the 300 series as ["a low-budget alternative for the 7xx series."](https://www.thinkwiki.org/wiki/Category:Models#ThinkPad_300_series)

![Red Hat CD](/posts/blog/images/redhat60/redhatcd.png)

Recently, I bought this big-box copy of Red Hat Linux 6.0 at Free Geek Twin Cities, a recycling center and thrift shop where I regularly volunteer here in Minneapolis. Today, Red Hat Enterprise Linux is the only operating system that still bears the Red Hat name, with Fedora being the successor to the more consumer-oriented Red Hat Linux. Red Hat Linux would continue to exist for a few years after this release, with the final version, 9, coming out in 2003. The version that I have, 6.0, was the first to use the GNOME 1.0 desktop environment. My copy also came with a bonus CD with plenty of additional applications. This version of Red Hat also came with KDE 1.1, so I was excited to try that out, as I had never used a version of KDE older than 4 (or a version of GNOME older than 2.)

But first, let's get the install started. I went ahead and inserted the CD into the ThinkPad, and made sure to put the boot floppy in for good measure since I couldn't remember if the machine was capable of booting from CDs. Red Hat 6.1 apparently came with a totally new, graphical installer, but this version was stuck with good old text mode.
![Red Hat installer](/posts/blog/images/redhat60/IMG_1768.JPEG)
![Red Hat installer](/posts/blog/images/redhat60/IMG_1778.JPEG)
I won't bore you with the details of the installation. I set it to install both GNOME and KDE, as well as all of the applications it had built in. 

![Red Hat login screen](/posts/blog/images/redhat60/IMG_1783.JPEG)
And it booted! But running at only 640x480... I spent a while messing around with the XF86Config file (which defines parameters of your graphics card and your monitor's supported resolutions,) but could not get the full resolution working, with attempting to force 800x600 resulting in X11 crashing and complaining that it was unable to find any supported video modes. Eventually, I decided to just leave it, as considering how notoriously difficult it was to get Linux to even boot in 1999, I was probably lucky to have a system that installed, booted, and got to a GUI on the first try.

![GNOME 1.0](/posts/blog/images/redhat60/IMG_1790.JPEG)
![KDE 1.1](/posts/blog/images/redhat60/IMG_1794.JPEG)
Here are the GNOME and KDE desktops, each with a window open. Both have very similar looking panels (taskbars), although they are not the same. The left and right arrow buttons on either side of the panel collapse it to either side of the screen for more screen real estate. Both also have a similar layout to CDE, another desktop environment that was common in the '90s.

One application that came bundled on the CD was StarOffice, a full office suite developed by Star Division, who were bought by Sun Microsystems in 1999, making this version, 5.0, one of the last versions pre-Sun. StarOffice was one of the few office suites that ran on Linux at the time, and its interface was really interesting. It basically had its own desktop and window system, start menu, taskbar, and web browser. 
![StarOffice home](/posts/blog/images/redhat60/IMG_1802.JPEG)
![StarWriter](/posts/blog/images/redhat60/IMG_1803.JPEG)

I had a bit of trouble getting past the install, as it kept asking for a product key that I didn't think I had, until I realized it was on a sticker on the front of the applications CD. On the off chance that anyone else needs a StarOffice 5.0 OEM product key, mine is GNJK-9WSN-JOOT-PQF2. 

Here are a couple more photos of the laptop, as well as some more pictures of Linux running on it. Thanks for reading :-)

![ThinkPad top](/posts/blog/images/redhat60/IMG_1804.JPEG)
![GIMP loading](/posts/blog/images/redhat60/IMG_1792.JPEG)
![GIMP interface](/posts/blog/images/redhat60/IMG_1793.JPEG)
![StarOffice loading](/posts/blog/images/redhat60/IMG_1800.JPEG)
![Application CD front](/posts/blog/images/redhat60/IMG_1788.JPEG)
![Application CD back](/posts/blog/images/redhat60/IMG_1801.JPEG)
