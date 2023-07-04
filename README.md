# Wifiduck_CJMCU_old
This is a wifiduck using old version (no locale option for languages of keyboard)  
* Tools by spacehuhn for hacking HID using wifi (wifiduck using CJMCU devices)
* Could be used to act as keyboard wireless with pre-programmed payload
* Devices : CJMCU, wifiducky DSTIKE, malduino
* Tested devices : CJMCU

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
* Download arduino and upload this code (select following port and type of board before uploading)
* Connect The two pins as :
  
* Run esp8266 flasher named as  :
 ESP8266Flasher.exe
* In operation, Change port com as COMx
* In config, change with the firmeware v2 or v3
* In Advanced, change bauderate as Y at the first step
* After successfull flashing, don't the two pins in the first step
  

