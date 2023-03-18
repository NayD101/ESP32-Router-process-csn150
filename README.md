# ESP32-Router-process-csn150


# Name of project 
ESP32 NAT Router


## Purpose 
Use the firmware provided from this project to use ESP32 as a NAT Router  
+ ESP32 can be used as WIFI Range Extender
+ Can be used to create a seperate WIFI network with different SSID from home network
+ Used for additonal WIFI for guest/IOT devices with different SSID 



## Equipment 
[ESP32 CAM](https://www.amazon.com/Aokin-ESP32-CAM-Development-Bluetooth-Arduino/dp/B08SLD8DKV/ref=sr_1_10?keywords=esp32%2Bcam&qid=1678904661&sr=8-10&th=1)
usb Micro data cable
Micro memory chip 


## Link for Documentation 

+ [github.Martin-ger](https://github.com/martin-ger/esp32_nat_router)

![youtube ESP32 video](https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Martin%20youtube.png)

## Steps That I followed 

!. [Download zip file from code section on github.Martin-ger](https://github.com/martin-ger/esp32_nat_router)
  [https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Step%201%20download%20Zip.PNG]

2. [Download this Flash Download Tool and The other 2 tools](https://www.espressif.com/en/support/download/other-tools) 

3. Once the the File has finished downloading click on downloads on file Explorer and right click to Extract the zip File

4. [Next you want to find and double click on your Flash download tool and open it](https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/ESP%20flash%20downlaod.PNG)
5. Select flash downlaod tool
 ![Select "Flash_download_tool_3.9.4" Application](https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Select%20application.PNG)

6. Next you will see a Windows screen pop when trying to open app, ingore the warning  select "more info" and procced to click "run anyway" 

  ![run anyway](https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Run%20Anyway.PNG)

7. Next Step is to configure this window before the tool is luanch. For the scope of this project we set the chip type to ESP32.

   ![Config window](https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Config%20drop%20down%20to%20Esp32.PNG)
   
8. You want to look at your ESP32 flash download tool window and set these configurations
(https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/ESP%2032%20tool%20Config.PNG)

9. You can find these paths by selecting the three dots to the right of tool window 

(https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Tool%20config.PNG)

10. Make Sure the load is in the order of *ALSO MAKE SURE YOUR ESP32 is connected by this POINT VIA MICRO USB CABLE* 
  +bootloader.bin
  +Partitions.bin
  +Firmware.bin

11. Please make sure your flash tool looks like the picture mention in Step 9 if you want your build to correctly load. 

12. Select Start on the Downlaod tool to proceed with build you should see a terminal next the tool

(https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Flash%20download%20tool.PNG)


13. Once load is succesfully finished please Unplug ESP32 for 10 seconds 

14. Plug in again after 10 seconds and open your Network settings your NAT_Router should pop up in your wifi settings

![Network properties](https://github.com/NayD101/ESP32-Router-process-csn150/blob/main/Network%20Router.PNG)


15. You want to connect to it and Open a internet browser 

16. In the url Enter "192.168.4.1" 

17. Once the page loads  you will presented with this Web Config Interface

![Web config interface](https://raw.githubusercontent.com/marci07iq/esp32_nat_router/master/ESP32_NAT_UI3.png)

  
 


## Problems 





