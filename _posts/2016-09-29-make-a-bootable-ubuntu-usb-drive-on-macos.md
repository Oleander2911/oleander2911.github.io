---
layout: post
title: Make a bootable Ubuntu USB using macOS.
---

**TL;DR:** After trying out Unetbootin and finding that my usb would not boot. I found an easy solution to the problem.


# Unetbootin not working?

I have been experiencing a weird problem with my newly installation of Ubuntu 16.04, if I started using the machine with more heavy tasks it would freeze and the only option was to do a cold restart.

I haven't been able to find a solution to this, but I read some place that it could be the iso used that could have been corrupted or something. So my next bed was to reinstall the system.

I tried out Unetbootin which was the only native option I knew of on macOS and it was also what Ubuntu official [documentation](http://www.ubuntu.com/download/desktop/create-a-usb-stick-on-mac-osx) suggested, after making the bootable drive with Unetbootin I tried booting it up, but all I was faced with was an error stating the following ***"failed to load.com 32 file menu.c32"***, it seems to be a "recent" bug which no one seems to care about.

My next move was trying out rufus the only problem with rufus is that only works on windows, and after installing Ubuntu I had no way to use rufus natively, I tried running rufus in wine, but it couldn't find the usb.

# Etcher my new go to.

I tried a couple of internet searches for alternatives and i found [Etcher](https://www.etcher.io), it looked nice, and seemed simple, and it was also my best bed at the moment.

And after going through the 3 small steps my usb was ready, i put it in the computer and finally it booted.
So if you need to make a bootable usb with ubuntu(and properly also other distros) this is the way to go.
