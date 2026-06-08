# Device Menus Overview V2.11

This document describes the menu structure and functionality of the device.

---

### Main menù

| Menu | Description |
|---------|-------------|
| **ESP S3 Module** | Menù for Esps3 Features |
| **Wifi** | Wifi features of main MCU BW16 |
| **Sniff** | All Wifi sniffere features of main MCU BW16 |
| **ScanWifi** | Bw16 Scan of wifi network , you need to use to update network list for other BW16 features|
| **SelectWifi** | You must select wifi to use most of the BW16 wifi functions |
| **Ble** | Bluetooth Low Energy BW16 operations |
| **I2C Modules**| Active functions of i2c module on BW16 |
| **Others** | Other functions of Main MCU |
| **Wifi Setting** | Change configuration of wifi settings |



## 📡  Sub menù: ESP-S3 Module

**Description:** Activates ESP-S3 functions and features.

### Submenus

| Submenu | Description | Status |
|---------|-------------|--------|
| **ESPS3 IR** | Infrared transmitter/receiver controls |
| **ESPS3 RF** | Radio frequency communication module (CC1101 features) |
| **ESPS3 WIFI** | Wireless network functions |
| **ESPS3 BT** | Bluetooth Low Energy (BLE) operations |
| **ESPS3 GPS** | Gps functions |
| **ESPS3 NRF** |  Sniff and more on NRF24 |
| **ESPS3 USB** | Duckyscript USB |
| **ESPS3 CHAMELION** | all API to connect and use CHAMELEON ULTRA via ble |
| **ESPS3 OCTOPRINT** | all API to connect and use octoprint connected to wifi |
| **AUTOMOTIVE RF** | decodes many car remote controls |
| **ESPS3 PN532** | copy and emulate tag nfc |
| **ESPS3 OTHERS** | more features |
| ** Bridge App To S3** | Use this command to connect your apk or fap to ThorChimera |
| **ESP serial STOP** | This function is in every menu, it is used to close the operations in progress if they remain active, by pressing it 4/5 times, if the LED flashes the ESP is again waiting for commands |

#### ESPS3 IR Submenu 
| Function | Description |
|----------|-------------|
| **IR ESP List** | List of saved ir signal and ready for Transmit |
| **IR RAW SAVE** | Wait , Receive and save to SD IR RAW signal (once at time) |
| **TV B GONE** | Turn off TVs|
| **IR DECODE ONLY** | Wait signal and decode (this feature not save any signal) |
| **IR RAW RECORDER** | Wait , Receive and save to SD IR MULTIPLE RAW signals (until you exit or 1 minute of inactivity) |
| **IR FAV ESP** | You can choose from webui your favorite signal , with this features  you can send your favourite ir signal  |


#### ESPS3 RF Submenu 
| Function | Description |
|----------|-------------|
|  **RF ESP List** | List of saved RF signal and ready for Transmit |
| **RF RAW SAVE 433** | Wait , Receive and save to SD RF RAW signal 433Mhz (once at time) |
| **Frequency Analyzer** | Wait signal and return main frequency found |
| **RF Fixed Code Scan** | Wait signal and decode (this feature not save any signal) |
| **RF Fixed Code SAVE** | Wait signal and decode and save only decoded signal |
| **433Mhz RF SCANNER** | This feature show graphic of 433mhz signal in real time| 
| **315Mhz RF SCANNER** | This feature show graphic of 315mhz signal in real time(experimental)| 
| **868Mhz RF SCANNER** | This feature show graphic of 868mhz signal in real time(experimental)| 
| **RF RAW SAVE 315** | Wait , Receive and save to SD RF RAW signal 315Mhz (once at time , experimental) |
| **RF RAW SAVE 868** | Wait , Receive and save to SD RF RAW signal 868Mhz (once at time, experimental) |
| **Replay RF** | This features wait any rf signal and resend it once |
| **IR RAW RECORDER** | Wait , Receive and save to SD RF MULTIPLE RAW signals (until you exit or 1 minute of inactivity) |
| **RF FAV ESP** | You can choose from webui your favorite signal , with this features  you can send your favourite RF signal  |




#### ESPS3 WiFi Submenu

**Description:** Activates WiFi functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **THOR WEB AP** | Activate web file manager and configuration |
| **Wifi IP** | See your network ip and global ip (require config file with credentials in SD) |
| **Network Scanner** | Scan all network and return all device with ip connected to your network (require config file with credentials in SD)  |
| **HandshakeSniff ESP** | Save Handshake to SD |





#### ESPS3 BT Submenu

**Description:** Activates Bluetooth functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **Bad Ble** | Ducky script via BLE |
| **Skimmer Finder** | Find any BLE card skimmer (HC-06/HC-05/HC-04 and others) |
| **Airtag Finder** | Find Airtag with distance, Find ipad/mac and iphone in lost mode or not conneted to internet |
| **BLE Scan** | return list of any ble device nearby |
| ** Flipper Scan** | find any flipper zero nearby |
| ** Meta Glasses**| find meta glasses nearby |




#### ESPS3 GPS Submenu

**Description:** Activates GPS functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **GPS INFO** | Find satellite and your position |
| **Wardriving** | The real wardriving dual band 5Ghz+2.4ghz |
| **Wardriving 2.4** | wardriving only 2.4Ghz |



#### ESPS3 NRF Submenu

**Description:** Activates NRF functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **NRF Spectrum** | Find any BLE/WIFI signal with graphics using nrf24 |


#### ESPS3 USB Submenu

**Description:** Activates USB functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **USB ESP List ** | with this features you have a selectable list from your scritpt in sd and you can send your favourite USB script with esp s3 usb to your pc/iphone/android and more |
| **USB FAV ESP ** | You can choose from webui your favorite script , with this features  you can send your favourite USB script with esp s3 usb to your pc/iphone/android and more  |



#### ESPS3 CHAMELION Submenu

**Description:** Activates CHAMELEON ULTRA functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **CHAM CONNECT ** | Must be first , connect your device to chameleon ultra via ble |
| **CHAM DISCONNECT ** | Disconnect your device to chameleon ultra |
| **ChamList EMULATE**| You use existing file saved to sd and emulate with Chameleon Ultra |
| **CHAM HF READ ** | You can see Data Tag HF |
| **CHAM LF READ ** | You can see Data Tag LF |
| **CHAM HF SAVE ** | You can see Data Tag HF and save to ThorChimera SD |
| **CHAM LF SAVE ** | You can see Data Tag LF and save to ThorChimera SD |
| **CHAM SEL SLOT ** | You can change slot of your Chameleon Ultra |
| **CHAM BATTERY ** | You can see battery status of Chameleon Ultra|
| **CHAM FACRESET** | Factory reset Chameleon Ultra |


#### ESPS3 OCTOPRINT Submenu

**Description:** Activates OCTOPRINT functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **OCTO Connect** | Must be first , connect your device to octoprint via wifi (you must setting your wifi credential in configuration file in sd card first and api key) |
| **OCTO Disconnect** | Disconnect your device to octoprint |
| **OCTO List Files** | List files of main directory in SD of octoprint and you can print file select file in list in this menu (max 60 files in main sd or buffer not find all files) (experimental , support space and any name of files) |
| **OCTO Home Z** | Home Z (you must use OCTO HOME XY first this command or printer will be in error) |
| **OCTO Home XY** | Home X and Y axis at same time |
| **OCTO Home X** | Home X |
| **OCTO Home Y** | Home Y |
| **OCTO Temp Bed** | You can set your temp bed here |
| **OCTO Temp Extruder** | You can set your temp Extruder here |
| **OCTO Status** | You can see the printer status here |
| **OCTO Move X** | Move Axis X |
| **OCTO Move Y** | Move Axis Y |
| **OCTO Move Z** | Move Axis Z |
| **OCTO Baby Z** | Change Baby Stepping while print |


#### ESPS3 AUTOMOTIVE RF Submenu

**Description:** Activates AUTOMOTIVE functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **START 433 ** | with this features you scan automotive RF remote controll in 433Mhz range  |
| **START 868 ** | with this features you scan automotive RF remote controll in 868Mhz range (experimental)  |
| **START 315 ** | with this features you scan automotive RF remote controll in 315Mhz range (experimental)  |
| ** STOP **| Force stop of all AUTOMOTIVE RF function (press 4/5 times and wait led blink) |







#### ESPS3 PN532 Submenu

**Description:** Activates PN532 functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **NFC SCAN ** | Scan and info of NFC Tags |
| **NFC DUMP ** | Copy and save NFC Tag to SD |
| **NFC EMULATE**| You use existing file saved to sd and emulate with NFC |
| **NFC WRITE**| You use existing file saved to sd and write only in compatible tags |






#### ESPS3 OTHERS Submenu

**Description:** Activates USB functions (Esps3 module).

### Submenus


| Function | Description |
|----------|-------------|
| **I2C SCANNER ** | scan any  i2c device connected ad return address (you need to conect any i2c device to to 3v3, GND, SDA, SCL) |
| **IC2 ACCELEROMETER ** | information about axis of accelerometer (you need to conect accelerometer adxl345 to 3v3, GND, SDA, SCL)  |
| **IC2 BUBBLELEVEL ** | Bubble that levelingthing with accelerometer (you need to conect accelerometer adxl345 to 3v3, GND, SDA, SCL) |
| **THOR AIRMOUSE ** | conect your phone/pc or other to esp bluetooth and use like mouse (you need to conect accelerometer adxl345 to 3v3, GND, SDA, SCL) |
| **GEIGER COUNTER ** | This function displays the millisievers detected by an analog Geiger counter and averages the msv in 5 seconds and 1 minute. (DO NOT CONNECT 5V TO THOR CHIMERA OR YOU WILL DESTROY YOUR DEVICE , GEIGER COUNTER MUST POWERED BY 3X SEPARATE NON RECHARGABLE AAA BATTERY) conect only GND and Pin 47 to GND and pin VIN of Geiger counter.|
| **ESP FIRMWARE V ** | Display firmware version of ESPS3 MCU every 5second |
| **FORMAT SD CARD** | Erase all files i SD CARD |
| **HARDWARE CHECK ** | Reboot ESPS3 and check main hardware |

////////


## 📶 Wifi

**Description:** Dualband wifi functions.

### Submenus

| Submenu | Description  |
|---------|-------------|
| **Deauth** | Deauth Selected Targhet | 
| **Deauth All** | Deauth all wifi scanned | 
| **AuthFlood** | Autentication Flood selected targhet | 
| **AssocFlood** | Association Flood selected targhet | 
| **RickrollSpam** | Spam hotspot rickroll list | 
| **Scan Stations** | Scan wifi stations | 
| **Deauth Station** | Deauth selected wifi station | 
| **AuthFlood Station** | Autentication Flood selected station | 
| **AssocFlood Station** | Association Flood selectedstation | 
| **AntiDeauth** | Autotarghet any deauthing device and flood it with Association flood packet (experimental)| 
| **Becon** | Other beacon spam | 
| **About** | Main info and credit of ThorChimera | 



---

## 🔌 Sniff

**Description:** Dualband wifi Sniffers.

### Submenus

| Submenu | Description  |
|---------|-------------|
| **Analyzer** | Graphic with all channel wifi in use (dualband) | 
| **PktMonitor** | One channel at once scan packet in channel in use (dualband) | 
| **AnalyzerText** | Wifi list with specs (dualband)  | 
| **AnalyzerMac** | Wifi list with specs and mac address (dualband) | 
| **Wifi All Info** | 1 Wifi at time all specs | 
| **CatDetector** | Find any deauth attack nearby (cat angry) | 
| **DeauthDetector** | Find any deauth attack nearby and visualize mac of attack device | 
| **DogFloodFinder** | Find any Association/Autentication flood attack nearby (dog angry) | 
| **AutenticatorSniff** | Find any Association/Autentication flood attack nearby with mac address of attack device | 
| **PwngridSniff** | Sniffer of Pwngochi devices | 
| **DistanceWifiSelect** | info of selected wifi and live graph of whether you are getting closer or further away | 
| **PinappleScan** | Sniffer of pinapple devices | 
| **Pinapple List** | List of pinnapple devices found | 




---

## 📶 Ble

**Description:** Activates BW16 Ble functions.

### Submenus

| Submenu | Description |
|---------|-------------|
| **Ble Spam** | BLE Spam for ios/android/windows |
| **MediaControl** | Controll your media with ble (play pause volume etc... |
| **BtPhotoANDR** | BLE shooter for android |
| **BtPhotoIOS** | BLE shooter for iphone |


---

## 💾 I2C Modules

**Description:** BW16 I2C modules operations.

### Submenus

| Submenu | Description  |
|---------|-------------|
| **ScreenOFF** | Turn Off the screen | 

---

## ⚙️ Others

**Description:** Device configuration and settings.

### Submenus

| Submenu | Description  |
|---------|-------------|
| **BatteryStatus** | Here you can see battery status of ThorChimera | 
| **PwnagochiAlert** | Spam Pwnagochi packet | 
| **PinappleSpam** | Spam Pinapple packet | 
| **SerialMonitor** | Monitor for serial | 
| **Serial2Monitor** | Monitor for serial2 | 
| **ResistorTool** | Toll to calculate resistor value from color band | 
| **ResistorToolSMD** | Tool to calculate resistor value smd from number on resistor | 
| **Chronometer** | Cronometer | 
| **Dice** | 6 Faces dice | 

---


**All experimental features are hardcoded and are limited by hardware**
