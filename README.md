﻿<h1 align="center">L Speed magisk</h1>

<p align="center">
<a href="https://forum.xda-developers.com/apps/l-speed">
<img src="https://img.shields.io/badge/XDA-Thread-orange.svg?style=flat-square"></a> 

<a href="https://t.me/LSpeedDiscussion">
<img src="https://img.shields.io/badge/Telegram-Group-blue.svg?style=flat-square"></a> 

<a href="https://lspeed2016.wordpress.com">
<img src="https://img.shields.io/badge/L%20Speed-Blog-blue.svg?style=flat-square"></a>
</p>

<div align="center">
  <strong>The most advanced Android tweaker.
</div>

<div align="center">
  <h3>
    <a href="https://github.com/Paget96/lspeed_magisk">
      Source Code
    </a>
    <span> | </span>
    <a href="https://forum.xda-developers.com/apps/l-speed">
      XDA
    </a>
  </h3>
</div>

## Introduction
L Speed is a modification that combines tweaks inside an intuitive module who aims to improve kernel with optimal parameter changes for the widest range of devices.
It's goal is to improve overall performance, reduce significant lags, extend battery life and improve your experience on Android. Fully customizable module with prebuit manager.
When we talk about the performances it'll improve your gaming experience (for example PUBG, Garena Free-fire, and bunch of others), otherside there is battery profile who aims to increase your Screen on time and idle time with minimal performance loss.
If you are unsure, simple use the balance profile which is a perfect balance between those two.
It's very simple to use, everything is well explained in the manager it self, every option have a info button beside it.
The mod will and should work on any device that meets its minimum requirement.
You only need a rooted Android device and proper installed busybox to function properly.

<div align="center">
**Module with prebuilt manager**

<img src="https://github.com/Magisk-Modules-Repo/lspeed/blob/master/screenshots/1.png" width="192" height="317"/> <img src="https://github.com/Magisk-Modules-Repo/lspeed/blob/master/screenshots/2.png" width="192" height="317"/> <img src="https://github.com/Magisk-Modules-Repo/lspeed/blob/master/screenshots/3.png" width="192" height="317"/> <img src="https://github.com/Magisk-Modules-Repo/lspeed/blob/master/screenshots/4.png" width="192" height="317"/>
</div>

**Requirements:**
1. Root (Magisk 18.0 +)
2. Properly installed busybox

## Downloads
* For stable and beta versions, download link is below
- https://github.com/Magisk-Modules-Repo/lspeed

* For canary builds, download link is below
- https://github.com/Magisk-Modules-Repo/lspeed/archive/master.zip
- Canary builds are bleeding edge builds and can contain bugs. Be aware of it, you flash this on your own. Those builds contains the changes till the latest commit on GitHub.

After downloading canary build you just have to repack zip, extract, go into master folder and zip all the files inside.
Uninstalling current version is necessary. 
After everything is done, flash the zip.

Please provide L Speed logs located in:
/data/lspeed/logs

And magisk logs, located in:
/data/cache/magisk.log

## Bug report
- If you are one of the users with the issues on your device (such as bootloop, device freeze) please get Magisk canary (because of logs), 
test the problematic build and pass me L Speed and Magisk log, logcat will be also welcomed. 
You can pass them on any links from below (Telegram is recommended)


**Links:**
- [xda-thread](https://forum.xda-developers.com/apps/l-speed)
- [Reddit](https://www.reddit.com/r/LSpeedOptimizer/)
- [Facebook page](https://www.facebook.com/LSpeedAndroidOptimizer)
- [Facebook group](https://www.facebook.com/groups/169281933668021/?source_id=1503157226676471)
- [Blog](https://lspeed2016.wordpress.com)
- [Instagram](https://instagram.com/p/BxUcz0zlVUj/?igshid=1ib59rrsrjffl)
- [Telegram group](https://t.me/LSpeedDiscussion)
- [Telegram channel](https://t.me/LSpeedChannel)
- [Translate](https://forum.xda-developers.com/apps/l-speed/translating-help-translating-l-speed-t3587252)
- [Telegram **My projects** channel](https://t.me/paget96_projects_channel)

- [Check my developer account and other apps](https://play.google.com/store/apps/dev?id=6924549437581780390&hl=en)

If you want, you can support me over [Paypal donate](https://paypal.me/Paget96), to support my work.

## Changelog 

**v1.2.1**
- This version have everything disabled by default (if clean install)
- Run script in background when executing on boot
- Added boot completed check
- Wait 1min 30secs after boot to set up parameters
- Enabled adreno idler on balanced profile
- Updated read_aheads for blocks
- Updated net speed+
- Improved disable debugging
- Added ms to log timing
- Fixed issues with Optimize button in manager
- Updated busybox check
- Updated code with POSIX syntax fixes
- Improved code
- Enabled full debug for this build

**v1.1**
- Increased optimize time to a bit more than 24h
- Improved device optimization
- Added user defined indicator
- Improved chanigng profiles
- Updated virtual memory tweaks
- Updated IO block optimization
- Updated logging