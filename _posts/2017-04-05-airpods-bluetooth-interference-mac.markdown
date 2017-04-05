---
layout: post
title:  "Troubleshoot: Poor AirPod Connection with Mac Mini"
date:   2017-04-05 09:22:07 -0400
categories: jekyll tech ccannon Apple AirPods MacMini
---
I recently received a pair of AirPods as a birthday present and I must say, they are incredible. However, I experienced some difficulty right away with connecting them to my Mac Mini. They would pair, but sound would come over broken, jumping from one ear to the other, with nothing clear coming through. I decided to contact Apple Support after trying the most basic troubleshooting I could think of; unpairing and repairing the AirPods from my AppleID, and pairing the AirPods directly to the Mac Mini.

### The Solution
Basically, after 4 different case numbers, we determined that the most likely cause of my issue was an abundance of Bluetooth interference from my previous generation Magic Keyboard, Magic Trackpad, and Magic Mouse. The final Apple Support advisor I spoke with suggested that I power off my keyboard and trackpad, using only the mouse to pair the AirPods. Once I did, music came in consistently clear like it hadn't before.

### The Troubleshooting Experience
I must give credit to Apple for their online support experience. Since I purchased my first Mac in 2013, the experience has simplified and become far more accessible. Save for one particular advisor (who advised me to turn my Mac off and on again, after I provided him my two previous case numbers), everyone I interacted with was polite and professional and, most importantly to me, provided me with the next most logical step to work through my problem. Finally, I called in to Apple to speak with a senior advisor, all previous interactions had been over chat. Seeing that we had exhausted the standard troubleshooting checklist, he decided to "think outside the box".

Overall, I'm very pleased that Apple has made support _even more_ accessible to its customers over the past several years. I think it is one of the great defining characteristics of an "Apple experience," and is a large factor in why I recommend Apple products so often. It is a great thing when you are facing a complex problem with your devices to be able to quickly reach a professional who's only goal is improving _your_ experience with _your_ device, not upsell you to a new device or sell and expensive and unnecessary "repair."

### The Problem
All Bluetooth devices operate in the global Industrial, Scientific, and Medical (ISM) GHz radio frequency band [1](https://en.m.wikipedia.org/wiki/Bluetooth). According to Apple, the Mac Mini utilizes Bluetooth 4.0 [1](http://www.apple.com/mac-mini/specs/) which operates in the 2.400GHz - 2.4835GHz range [3](https://www.bluetooth.com/specifications/adopted-specifications/legacy-specifications). This specification results in 78 RF channels spaced at 1 MHz across the range. With the amount of traffic required to run audio on 2 separate AirPods as well as maintain a connection and receive data from 3 separate devices, it is not inconceivable that cross-talk would be an issue. BLuetooth 5 promises to increase "broadcast messaging capacity by 800%". According to a report from MacRumor's, Apple intends to bring Bluetooth 5 to new devices beginning this year [5](https://www.macrumors.com/2016/12/07/bluetooth-5-officially-approved/), so perhaps the next iteration of AirPods with Apple's promised new pro level desktops will solve this problem overall [6](http://daringfireball.net/2017/04/the_mac_pro_lives).

### References
\[1\] [Wikipedia Bluetooth Page](https://en.m.wikipedia.org/wiki/Bluetooth)

\[2\] [Mac Mini Technical Specifications](http://www.apple.com/mac-mini/specs/)

\[3\] [Bluetooth Legacy Specifications](https://www.bluetooth.com/specifications/adopted-specifications/legacy-specifications)

\[4\] [What is Bluetooth](https://www.bluetooth.com/what-is-bluetooth-technology/how-it-works)

\[5\] [Bluetooth 5 Coming to Apple](https://www.macrumors.com/2016/12/07/bluetooth-5-officially-approved/)

\[6\] [Daring Fireball on new Mac Pro](http://daringfireball.net/2017/04/the_mac_pro_lives)
