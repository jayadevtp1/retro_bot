---
title: "Desktop Bot"
github: "https://github.com/jayadevtp1/retro_bot/"
description: "A mini AI companion robot that sits on my desk. It has an animated face, a rotating head that turns and dances, and built-in voice so I can chat. A front eye cam to see me."
created_at: "2026-11-21"
total_time: "15h 30m"




---

# November 21, 2026: Desktop Bot Concept in Blender
<!-- fabricate:entry 3582 -->

Initially i converted my Desktop Bot Concept/idea in Blender




The main design idea of the bot is from the m5stackchan ai desktop bot and an old crt monitor.
The size of 66mm x 60mm x 60mm with a 2 inch lcd display.I thing that will be nice for this . 
A small cam a the top-center or bottom-center of the front . Some eye movements, clock ui and temperature.. etc are some main features in the display part.




![](https://fabricate.hackclub-assets.com/c6f7a8b666fe96907ad0dd7ce2bbe19becdcecd7f7ee882b3c92a7391440e085/image-png/87.png)

**Total time spent: 4h**

# November 23, 2026: Schematic completed
<!-- fabricate:entry 3748 -->

Completed schematic diagram 




I wired the esp32 module , mpu6050, max98357,1nmp441 ..etc . The capacitive toch pad and new modules if wanted then I will connect that to the headers i attached . That is the real reason for adding the headers.




![](https://fabricate.hackclub-assets.com/b7fcb3499c7044f8d4e18a25f7d5fc202071e3e6366b76f3a5375e59d243a494/image-png/89.png)

**Total time spent: 3h**

# November 23, 2026 (entry 2): Routed the PCB
<!-- fabricate:entry 3758 -->

While doing the PCB routing i noticed that the mic module must not place with the PCB that i think it will affect the voice quality so I place a 6 pin header in the PCB without editing the schematic diagram. I think due to the PCB size i think I want to increase the size of the case .
.




![](https://fabricate.hackclub-assets.com/d9481a45794cb687a97fe0e825a291ac71874b41351a1f7b910329aa0ff9c425/image-png/93.png)

**Total time spent: 3h**

# November 24, 2026: Bot Body Updation
<!-- fabricate:entry 3811 -->

Bot body updated based on display and PCB size and added display holding and PCB holding space . 
Esp32 programing port and attach a antenna for fancy. The RGB LED is placed on the top .While building the case i think that i forgot to add battery and battery charging circuits.




![](https://fabricate.hackclub-assets.com/7e185daa3959a240fb1a2687434444d044646d7e5db5f73abfbb42f96267ba45/image-png/95.png)
![](https://fabricate.hackclub-assets.com/0a386948734704f9e5c2a45bda477eb8831e215c5aeedd401c65cc24df6a1e5c/image-png/97.png)
![](https://fabricate.hackclub-assets.com/7323b2d8608d52fa3c4ca1e35ab7af89a86d3f5b4b3f31467c3c97804b3ddd08/image-png/98.png)

**Total time spent: 2h**

# November 24, 2026 (entry 2): Added Battery charging
<!-- fabricate:entry 3828 -->

Added TP4056 Battery charging circuits and Some unnoticed error in the schematic and edited PCB rooting .
Created a bom file based the PCB. I use robu.in for purchasing item


![](https://fabricate.hackclub-assets.com/8e8d7a33dc809bff701840a2120afb647fd8ded76e65673900e4c27c6af602d1/image-png/100.png)
![](https://fabricate.hackclub-assets.com/f5336c00064348fe4171f2df6c7074900e8e228627ad313c2f50d67ca0915696/image-png/99.png)

**Total time spent: 2h 30m**

# November 25, 2026: Edited the case
<!-- fabricate:entry 3887 -->

Added some bass reflex vent on the both sides of the the model for mic and speaker . The all parts are connected to the PCB using jumper wire or normal wires so I didn't give exact space for other components like speaker,battery and mic.

![](https://fabricate.hackclub-assets.com/ebb143078ad13698b2849b70c2c2231d42fa5b0bc35b12bccbee79f9cf8205f0/image-png/105.png)

**Total time spent: 1h**
