---
layout: post
title: "A Foray into the Internet of Things"
date: "2018-11-10 15:12:11 -0500"
en: true
---

The Raspberry Pi Zero W bills itself as a $10 computer.  Well... its' a $10 computer without memory for an operating
system, power supply, display, or needed ports for peripherals.  Part of the appeal to me is that minimalism. The thing is
tiny!  I could fit half a dozen of them inside the space taken up by a cell phone, possibly quite a few more depending on the
model.

I ordered the tiny device several weeks ago after seeing some incredible projects online--from a scanning electron
microscope to a portable panic button, the possibilities are virtually limitless.  I confess I never 
understood the whole IoT thing.  The internet has been around for longer than I have been alive, but
it was something 'other people' used.  I embraced tech early in life, but in many ways, I have always been behind the times.  
My family got internet when I was in grade school, which completely changed the way I lived my life.  I remember times without 
the internet with fondness.  Call me old-fashioned (or just plain old), but those were good times.  
Having friends over to play Super Nintendo, spending evenings playing outside, snail mailing letters, and mail-order catalogs.
To call the internet a bad thing would be a misnomer.  My life has completely changed since the internet--and in many 
ways improved.  Email, online video games, streaming music and video, GitHub, scholarly articles, social media,
and various web applications all have a role in my life thanks entirely to this incredible innovation.
My tardiness to the Internet party parallels my tardiness to the smartphone party.
I obtained an iPhone about 5 years ago--a full 5 years after the release of the first iPhone in 2007.
IoT has been in use in agriculture, medicine, enterprise, home electronics, and other 
applications for many years, yet I am just now getting into the game.  This is such an exciting time
to be alive, and we are merely scratching the surface of what is possible!

Beyond getting nostalgic about my childhood thanks to retro game platforms build with the Pi,
I did some research on the needed steps to get it running.  Etcher installed: check, dietpi image: check, 
microSD card flashed: check, ssh file added: check, wifi credentials in wpa_supplicant.conf: check.  
About a week ago, the Pi itself came in the mail.  I was as giddy as a child on Christmas.  Inserting the microSD card 
and attempting to boot the device worked as expected.  However, the device didn't connect to the wifi.  

After a bit of searching on the internet, it became apparent that running an update would be necessary to get the 
wifi chip on the card working.  Alas, I am hamstrung until the mini HDMI to HDMI converter comes in.
I can't SSH into it since it's not connecting to the internet.  I'm tempted to plug in a keyboard and attempt 
to update the thing without being able to see what I am doing--a far too literal shot in the dark.
Might also try adding a couple of lines to my .bashrc on the image.

More updates to come!
