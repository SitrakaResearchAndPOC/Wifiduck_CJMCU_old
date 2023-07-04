# Wifiduck_CJMCU_old
This is a wifiduck using old version (no locale option for languages of keyboard)  
* Tools by spacehuhn for hacking HID using wifi (wifiduck using CJMCU devices)
* Could be used to act as keyboard wireless with pre-programmed payload
* Devices : CJMCU, wifiducky DSTIKE, malduino
* Tested devices : CJMCU
<img src="https://github.com/SitrakaResearchAndPOC/Wifiduck_CJMCU_old/blob/main/cjmcu1.jpeg" width="250px" align="center">

# Installing driver of USB (could be CP21x, FT23X, CH340G, PL23X)
(In my case, it's [CP21x](https://drive.google.com/file/d/18dX5ws61_A4EaHKuIYNDSMMeMPuJHZG5/view?usp=drive_link))
* [CH34xG](https://www.wch-ic.com/downloads/CH341SER_ZIP.html)
* [FTDI and FT232RL](https://ftdichip.com/drivers/)
* [CP210x](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)

# Finding port of CJMCU
* Plug CJMCU
* search : "devices manager" and click it
* click "Ports (COM and LTP)"
* remind the number of port come noted as COMX
* click on COMx and click "all parameters" memories the baudrates note as Y 
* Close all

# Downloading firmeware of esp8266_wifi_duck
* [esp8266_wifi_duck_4mb.bin](https://drive.google.com/file/d/1dyYwcLWXgXHHTSlG2xHnXsv1elhltd6t/view?usp=sharing)
  
# Installation ESP8266Flasher
* Download [esp8266Flasher](https://drive.google.com/file/d/1YC0DqRsgMTjVpCc77wQt9xKFKphjFWGM/view?usp=drive_link)
* Launch ESP8266Flasher.exe

# Flashing esp8266_wifi_duck
* Download Arduino and upload this code [step1](https://github.com/SitrakaResearchAndPOC/Wifiduck_CJMCU_old/blob/main/step1.ino)  (select following port and type of board before uploading) 
* Connect The two pins as :
<img src="https://github.com/SitrakaResearchAndPOC/Wifiduck_CJMCU_old/blob/main/cjmcu2.jpeg" width="750px" align="center">
<img src="https://github.com/SitrakaResearchAndPOC/Wifiduck_CJMCU_old/blob/main/cjmcu3.jpeg" width="350px" align="center"></img>
* Run esp8266 flasher named as  : ESP8266Flasher.exe
* In operation, Change port com as COMx
* In config, change with the firmeware esp8266_wifi_duck
* In Advanced, change bauderate as Y at the first step
* After successfull flashing, don't the two pins in the first step
* Upload this code [arduino_ducky](https://github.com/SitrakaResearchAndPOC/Wifiduck_CJMCU_old/blob/main/arduino_wifi_duck.ino)  (select following port and type of board before uploading)
 
  
# Documentations
* https://github.com/TheMMcOfficial/WiFiDuck-for-CJMCU-3212
* https://github.com/puckk/CJMCU-3212
* https://github.com/TheMMcOfficial/CJMCU-3212-wifi_ducky
</br> </br>

* https://github.com/TheMMcOfficial/WiFiDuck-for-CJMCU-3212/blob/master/test.script
* https://github.com/TheMMcOfficial/WiFiDuck-for-CJMCU-3212/tree/master/atmega_duck
* https://github.com/puckk/CJMCU-3212
</br> </br>
  
* https://github.com/Insight1620/CJMCU-BadUSB
* https://github.com/robertio/DM-3212-Badusb/blob/master/README.md
* https://github.com/gidalo/CJMCU-BadUsb-keyboard-ITA-layout-lib
* https://github.com/Insight1620/CJMCU-BadUSB
* https://github.com/Insight1620/CJMCU-BadUSB/commit/7242d8dd9e7ad2ba3751ede62c154e57d97315b4
* https://github.com/mharjac/bad_ducky
* https://github.com/asciiterminal/CJMCU_ATMEGA32U4_BADUSB
</br> </br>

    
* https://github.com/robertio/DM-3212-Badusb
* https://github.com/SpacehuhnTech/WiFiDuck/issues/30
* https://www.youtube.com/watch?v=G-Z2rf_AN-c&t=142s
* https://github.com/SpacehuhnTech/WiFiDuck#translate-keyboard-layout
* https://github.com/spacehuhn/wifi_ducky/blob/master/arduino_wifi_duck/arduino_wifi_duck.ino
* https://github.com/spacehuhn/wifi_ducky
</br> </br>

  
* https://www.youtube.com/watch?v=tU3NHCy0VU8
* https://www.youtube.com/watch?v=BNcL5L2xMdI
* https://www.youtube.com/watch?v=unaF6OSP7uc
</br> </br>


