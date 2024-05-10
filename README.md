![Logo](https://github.com/r4d10n/esprit/blob/main/renders/logo.png)
# ESPRIT
ESP Radio Interface - Through Hole version with ESP32 DOIT devboard (based on [ESPRI](https://github.com/kamilsss655/ESPRI) project)

ESPRI project provides an integrated Digital Audio / Programming Interface for Quangsheng UV-K5, Baofeng UV-5R and other Kenwood-style connector radios, similar to the excellent [AIOC](https://github.com/skuep/AIOC) project. With ESP32 offering WiFi/Bluetooth connectivity,  the possibilities are endless !

Since Lolin32 Lite is not common in this part of the world and SMD sourcing / assembly is still cumbersome, we've attempted a Through Hole version for the most common 30 pin [ESP32 DOIT board](https://mischianti.org/doit-esp32-dev-kit-v1-high-resolution-pinout-and-specs/).

Changes:

- Since there are a lot of unpopulated I/Os, we've added 0.91" OLED, couple of LEDs, Switches and one more Touchpad Button. 
- The ADC/DAC IO pins have been broken out to a header
- Header Pins for Radio PWR, 5v and 3.3v 
- SMD 2N7002 has been replaced with THT 2N7000  

[[Interactive BOM]](https://htmlpreview.github.io/?https://github.com/r4d10n/esprit/blob/main/ibom/ibom.html) - [[Schematics]](https://kicanvas.org/?github=https://github.com/r4d10n/esprit/blob/main/espri-doit.kicad_sch) - [[PCB]](https://kicanvas.org/?github=https://github.com/r4d10n/esprit/blob/main/espri-doit.kicad_pcb) - [[Gerbers]](https://github.com/r4d10n/esprit/blob/main/production/espri-doit.zip)

![Top Render](https://github.com/r4d10n/esprit/blob/main/renders/espri-doit-top.png)
![Bottom Render](https://github.com/r4d10n/esprit/blob/main/renders/espri-doit-bot.png)
![Top PCB Render](https://github.com/r4d10n/esprit/blob/main/renders/espri-doit-pcb-top.png)
![Bottom PCB Render](https://github.com/r4d10n/esprit/blob/main/renders/espri-doit-pcb-bot.png)
