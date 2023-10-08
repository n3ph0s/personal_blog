---
title: "My Journey to Linux"
date: 2022-07-13T01:32:51+08:00
draft: false
toc: false
cover: /assets/linux.jpeg
tags:
  - linux
---



This is the story of my journey from being a loyal Apple user for nearly 20 years when 1 year ago I decided to completely leave the Apple ecosystem and move to Linux full-time.

The article will provide an overview of the many small decisions that I made from mid-2021 when I got a Lenovo laptop and installed PopOS 20.04 on it.

## Background

To provide some context, it was around 2000 when I decided to move away from Windows (the last good Windows OS in my opinion was Windows XP) and my first foray into Apple was an iMac (The tangerine colour I believe) and over the years I have had several MacBook Pros including the 17inch model which was a beast and lasted for more years than I can recall. It was, however, the last and probably the most expensive device over the time was the top of line, MBP Pro 13 inch Retina with Touch Bar and fully spec'd out and it was a lemon. The battery swelled, I took it to Apple to get it repaired and then it just got worse and worse from there and it became very evident that the quality that made the original Apple so good, went away when Steve Jobs passed and under the reign of Tim Cook the innovation and quality went south.

It was at that point that I decided to leave the Apple Galaxy and not just the computer, but the mobile and tablet landscape as well and switched to a custom ROM Android and Linux and when reflecting on it, I should have done this a lot sooner. Platform lockdown, software bloat and general lack of privacy are actual things and it is costly.

I did briefly consider Windows 10 as well, very shortly (about 30 seconds) before dismissing that as a viable option.

Normally when looking to make a change such as switching Operating Systems, there are at least 3 areas that need to be considered which are hardware, software and data, but this for me was a lot easier as the hardware was completely unstable at the point of time that I went out and bought the Lenovo laptop, as my current Apple machine was having several kernel panics a day. I started ensuring that all data was backed up and the key challenges were related to software and peripherals that I will cover later in the article.

### Ideology

When you say to people that you are running Linux, they often believe that it is related to an ideology such as "Free and Open Source Software" or anti-large technology companies, but this isn't my case. 

I do have strong views related to Open Source Software, but I am not one of those zealots that refuses to use commercial software and will only use Free and Open Source, but what I do care about is the ability to access data that I created without being locked into a single platform/system as my needs change over the years.

My choice of technology is related to my computing needs and knowledge at that particular time in my life. Windows was good in the 90s and Macs for the next 20 years, but now, Linux is my preferred choice and for the foreseeable future.

## Hardware

Normally, this would have been the longest part of the overall experience as I looked for a machine that would meet all my requirements, but this was very quick as I had a malfunctioning machine and went to a Harvey Norman in Singapore and from the limited selection that they had, I chose a Lenovo ThinkPad which had reasonable specifications and I had a reasonably high level of confidence that it would support Linux. 

I was surprised how little support the big providers have for Linux Desktop, but thankfully the one that I got worked and I haven't had any issues with it to date. 

Once I had been using it for a few months, I then decided to upgrade the RAM and hard disk which I was able to do myself, which is something that I used to do a lot in my early days with computing, but when I started using a Mac, this became a non-starter as in the early days, it was possible, but difficult and Apple made it even more difficult to near on impossible in the recent years. Even trying to repurpose an old machine is now near impossible.

One thing that I truly did come to appreciate is that I don't need a laptop anymore as I am more than capable of doing basic tasks on my smartphone or tablet. I am writing this on my phone with an external keyboard and for simple tasks, the need for a laptop becomes less important especially given that I predominately work remotely and travel has stopped. My next machine will be a desktop from System76 which is an independent computer maker that specializes in Linux-compatible hardware.

### Peripherals

The main peripherals that I had were a portable ScanSnap Scanner as well as a desktop version for larger jobs, which unfortunately the manufacturer doesn't provide Linux drivers, but I was able to find a way to port the drivers across and have both of them working, but not as seamless as they do on either a Mac or Windows as some of the advanced functionality isn't supported, but at the end of the day, the key task is scanning and this works.

The other was a Kensington trackball which worked when plugged in but I wasn't able to use the software that comes with the product to program the usage of the buttons, but I did find how to program them at the lower level and have a script that autodetects when the trackball is connected which runs and configures it to exactly how I want it to function. 

Everything else such as my Logitech Webcam, Bluetooth headphones and remote wireless cards, all work natively without any issue at all.

## Software

As I mentioned earlier, I chose PopOS as my operating system as it is based on Ubuntu which has a very large repository of software available and nearly every Open Source project provides a \*.deb package that can be easily installed.

The next challenge was to find suitable software to replace those that had become stables of what I used daily on my Mac.

### Note-Taking Apps

A key staple of my computing needs is my note-taking software and for this, I use two main products which are Obsidian and Standard Notes.  Standard Notes is my key for daily notes as it syncs securely across all my devices and this would become my only note-taking application if they allowed embedded images and backlinks.

On my Mac previously I had tried several variations of note-taking applications ranging from Evernote which I was a strong supporter of until they announced some changes to their policy that had security and privacy implications and then I moved off that platform and tried others such as Bear and Notion, but at the end of the day, what I need is the ability to take plain-text notes, back them up and make changes to them independent of the application that they were created in.

### Web Browser

I have been using Firefox for many years as I never really got into using Safari so migrating bookmarks was no drama at all. 

I run two browsers on Linux, which is Firefox for my everyday work and Chromium for specific tasks that require a Chrome-based browser.

### Music

This was quite easy as despite having a decent collection of MP3s I predominately listen to music online and this is either via Spotify, but more recently I have been using Nuclear which is getting more stable by the day. I never really got into Apple Music so thankfully I avoided that challenge.

### Text Editors and IDEs

This may seem tragic to some, but for the last couple of years, I have become a VIM advocate as this is a very powerful text editor and it just works. From an IDE perspective, I use Wing Pro for Python which is fully supported on Linux but there is a good selection of other IDEs that have native support for Linux.

### Video

For as long as I can remember I have always used VLC as it works well for video consumption, can download video streams and works on every platform, I even have it installed on my mobile device.

I have done some video editing in the past but there is no shortage of tools for this on Linux with the key one being OBS Studio which is predominately what I use now, but there is also KDEnlive which I have heard good things about but have not personally tried.

I will admit that there is a lot of very good software for Mac users in the Video editing space and for those who are video professionals, I can see the appeal of staying on a Mac and not moving to Linux.

### Image Editors

I am by no means a graphic designer so my requirements for image editors are pretty basic and even though on the Mac I did use Pixelmator, this was nowhere near its full capacity for this today I use Gimp and Inkscape and this supports all the possible formats and image editing requirements that I have.

### Password Manager

This is a big one for me as I have a lot of passwords and initially, I was using 1Password7 but I made the switch to BitWarden a couple of years ago and this has both a native client and web plugins.

### Communications

Thankfully I stopped using iMessage a long time ago and moved to Signal and this was an easy switch as it has a native client. 

For work-related communications, these are predominately Google Meet, Zoom or Microsoft Teams and they all work, although, with Microsoft Teams, it is not possible to share just a Window (not sure if that is an issue on Mac) as I am just a guest at these meetings, with Microsoft becoming more friendly towards Linux in recent years, I am confident that this will improve over time.

## Data

I was a hardcore user of iCloud but stopped using that heavily a few years ago as a paying customer for the service, it was just plain awful from a user experience perspective, especially when compared to other services such as Dropbox and OneDrive which were leaps and bounds ahead and were able to properly synchronize data across multiple devices.

As I was a Google user, I moved all my working files to Google Drive, but have since started to move this to a self-hosted platform.

### Office Suite

For work, I use Google Docs which works everywhere and has no issues with that at all, and I have found that LibreOffice is more than capable of doing all the core functions that I need with regards to spreadsheets, word processing on the home front.

### eBooks

Thankfully I never really got into Apple iBooks, as I was heavy into the Kindle ecosystem, but the challenge with this is that they are digitally locked into Amazon and a few of the books in recent times have suddenly disappeared which I can only believe are related to changes with the distribution rights of the books so in recent times, I have decided to only purchase DRM Free content and thankfully most of the books I buy are technical so I can get this from publishers such as No Press Starch and have the freedom to read these on multiple platforms.

## Conclusion

My migration to Linux as a result of prolonged hardware issues and poor customer service from Apple, which in hindsight is a blessing. 

I have a productive setup, with a machine with decent battery life, that I was able to upgrade so it now has great specs, all at a fraction of the cost of my previous MBP. My files are saved in standard, open formats, and I will be able to open them in the future.

During the last year, this setup has given me way fewer headaches and stress than what Apple was giving me and while it is not perfect, it is stable, efficient, very fast and so much cheaper.

Every user will have different mileage and I am not advocating that everyone migrate to Linux, as being technical did help me find and solve a few quirks, but in general, I had way fewer challenges than I expected and have been very pleasantly surprised.

For those who are sitting on the fence as to whether to try Linux, if you have an old machine lying around, breathe some new life into it and you may be pleasantly surprised, what have you got to lose?
