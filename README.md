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

# Downloading firmeware of deauther (v2 or v3)
* [v2](https://drive.google.com/file/d/1SDlyzD_QpOFj55N8Bah1HXs3y6TlexMn/view?usp=drive_link)
* [v3](https://drive.google.com/file/d/1WL7oKunPQWnsbr8DNvbqR_WbKbHOmUb9/view?usp=drive_link)
  
# Installation ESP8266Flasher
* Download [esp8266Flasher](https://drive.google.com/file/d/1YC0DqRsgMTjVpCc77wQt9xKFKphjFWGM/view?usp=drive_link)
* Launch ESP8266Flasher.exe

# Flashing deauther 
* Connect D3 with GND
* Run NodeMCU flasher at  :
  nodemcu-flasher-master\nodemcu-flasher-master\Win64\Release\ESP8266Flasher.exe
  or
  nodemcu-flasher-master\nodemcu-flasher-master\Win32\Release\ESP8266Flasher.exe
* In operation, Change port com as COMx
* In config, change with the firmeware v2 or v3
* In Advanced, change bauderate as Y at the first step
* After successfull flashing, don't connect D3 with GND anymore
  

