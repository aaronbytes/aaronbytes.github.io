---
title: "Living Room Gaming ft. Bazzite"
date: 2025-10-06T22:16:16-07:00
draft: true # Set 'false' to publish
tableOfContents: false # Enable/disable Table of Contents
description: ''
categories:
  - computers
  - linux
  - bazzite
  - gaming
tags:
  - pc
---

# The Idea
I primarily play single player games (RPGs, FPS, Adventure Games) and for me the things that matter the most are: 

* Grapics fidelity (4K, High/Ultra Settings)
* 60 FPS target
* Ability to use Mods
* Ease of use
* Ability to play from the couch

The second and third points are often difficult to achieve on consoles. But consoles have the upper hand on the final two points. 

I've owned a Steam Deck almost since launch and that device made it clear that it was possible to achieve some of the strong points of a console on PC platform. While the Steam Deck often struggles with the first two points, it becomes clear that with more capable hardware one could accomplish all of the points above. Before the Steam Deck I dreamed of how great an "Xbox Mode" for Windows would be, looks like Microsoft [agrees](https://www.xbox.com/en-US/handhelds/rog-xbox-ally)!

## Precursor
A couple of years ago I explored couch PC gaming. I already had a gaming PC in a bedroom but I wanted to be able to use the PC from the living room. I explored streaming solutions such as [Moonlight](https://moonlight-stream.org/) and [Steam's Remote Play](https://store.steampowered.com/remoteplay). However at the time I found the latency for 1440p HDR content to be too high for my liking. 

I then found out about [HDBaseT](https://en.wikipedia.org/wiki/HDBaseT) which allows for carrying an HDMI signal over a standard CAT 5e Ethernet cable. I picked up [this](https://www.gofanco.com/hdbaset-hdmi-2-0-extender-with-hdr-hdbaset-hdr.html) HDBaseT HDMI 2.0 Extender which worked perfectly to get the signal from the gaming PC in my office to my living room. I then paired this with a USB 2.0 over Ethernet extender to allow me to plug in an Xbox Wireless Adapter to resolve range issues with with the wireless controller. 

Whenever I would play games, I'd turn on the PC and launch Steam Big Picture mode on the TV.

This solution worked good enough, but I wanted a more seamless experience. Something where I could just turn on the PC and boot straight into Big Picture Mode. Since I used the gaming PC in the office for normal browsing as well as gaming, I didn't want it to automatically boot into Steam. Thus the motivation to build a dedicated living room PC.

# Hardware

## Components

Type | Component | 
-----|-----------
Case | Fractal Design Ridge
CPU | AMD Ryzen 5 7600x
GPU | PowerColor AMD RX 9070 XT Reaper
Motherboard | ASRock B650I Lightning Wifi AM5
RAM | 32GB TeamGroup T-Force Vulcan DDR5
SSD | 2TB TeamGroup MP44Q NVMe SSD
PSU | Corsair SF850
Cooler | Thermalright AXP90 X47 Full Copper

[PcPartPicker](https://pcpartpicker.com/user/aaramirez24/saved/PRZfFT)

I'm a huge fan of the Mini ITX form factor and I would say my ethos towards PC building is to strive for compute density. While there are definately smaller cases available such as the [SFF Time U-ITX](https://www.sfftime.com/product-page/u-itx-black), the Ridge is easy to work in and available at my local Micro Center. 

While this is subjective the Ridge is in my opinon a pretty sleek looking design. The fabric front fits in nicely in my entertainment center and definately has the "wife approval factor". That being said it is larger than an OG PS5 which is already quite the unit. 

That being said this case still imposes some restrictions on component choice. Notably the PSU was rather difficult to shop for as there aren't many 700+ watt PSUs on the market from reputable brands. Corsair's SF series appears to be a common choice, but this unit was not cheap. I tried to cheap out by buying refurbished units from Corsair and first UPS apparently destroyed the package, on the second try Corsair sent me a completely different PSU. I finally gave up and bought a new unit from Micro Center.

This case also limits us in terms of GPU, but since this PC is going in the living room I wasn't going to go high end and a three slot card was not under consideration. I went with the Power Color 9070 XT as this was a two slot card that in benchmarks was easily capable of 4K 60fps in most modern games. The CPU was picked for its thermals and lower power consumption while again still be capable of 4K gaming. 


"Mods" - Improving the asthetics with 3D printed feet (Also improves airflow)
	- Improving airflow using a 3D printed fan shroud
### Mods



# Software
Since I am targeting a console-like experience, I wanted to experiment with an operating system similar to what is on the Steam Deck. I had heard about [Bazzite](https://bazzite.gg/) which is an *immutable* Linux distro geared towards gaming. 

About a year ago I made the move towards using a Linux machine as my daily driver. I settled on [Fedora](https://www.fedoraproject.org/) running on a [Framework 13](https://frame.work/laptop13). If you're not familiar with Framework, they are an amazing company focused on building user repairable consumer electronics. I considered a Macbook Air as well as PCs on the Snapdragon Elite X platform, mainly because I wanted something thin, light & power efficient. Ultimately the Framework & Fedora combo more closely aligned with my values of repairability & openness. Using Fedora drove me to dislike Windows and to an extent even MacOS, which made Bazzite super appealing. 

Bazzite has been rapidly gaining popularity amongst the gaming community. But if you are unfamiliar, the key advantage is that it can be configured with Steam pre-installed and to boot directly into Steam Gaming Mode. This lets us effectively have the Steam Deck experience on any modern PC. 

Installing Bazzite is super simple. Simply answer some questions, burn the ISO onto a thumbdrive and boot from the thumbdrive. The modern Linux install experience is relatively painless and streamlined. However I was impressed that from booting into the installer to logging into Steam took *~10 minutes*. I haven't installed Windows in a couple of years, but I can't imagine that being anywhere near as smooth or quick as the Bazzite install experience. 

# Conclusion
Thermal Challenge - Undervolting to keep temps in line

Overall I'm really pleased with this setup. I've been having a blast playing Shin Megami Tensei V Vengeance on it. While not the most demanding game it's ran perfectly on Bazzite. As a plus, I can play this on my steam deck while on the go and my progress syncs seamlessly with Steam Cloud. This combination truly makes it feel like I can have my games wherever I am. 

As a follow up I'd be interested in trying to steam games from this PC to my Steam Deck while away from home. 

