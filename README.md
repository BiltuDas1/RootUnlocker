[![SL Scan](https://github.com/BiltuDas1/RootUnlocker/actions/workflows/shiftleft-analysis.yml/badge.svg?branch=main)](https://github.com/BiltuDas1/RootUnlocker/actions/workflows/shiftleft-analysis.yml)
[![Donate](https://img.shields.io/badge/Buy%20me%20a-Coffee-blue.svg)](https://www.buymeacoffee.com/stopback)
# Root Unlocker
Root Downloader is a Windows Program which helps you to unlock Root Into your Android Device using One click.  
**Please Note: before installing TWRP make sure that your device bootloader is Unlocked. If you want to unlock the bootloader then [check this repo](https://github.com/BiltuDas1/unlock-Bootloader)**  

# How to Root using Root Unlocker?

### Pre-Requesting
[TWRP Installer](https://github.com/BiltuDas1/RootUnlocker/tree/main/Installer)  
[TWRP for aio_row](https://github.com/BiltuDas1/RootUnlocker/tree/main/TWRPAIO)  
[SuperSU.zip](https://github.com/BiltuDas1/RootUnlocker/tree/main/SuperSU)  


1. Connect Your Android Device to your PC using a USB Cable  
2. [Computer] **Install Driver of Your Andorid OS and Turn on USB Debugging(ADB)** [No Driver?](#how-to-find-a-device-driver)  
3. [Computer] Create a folder on Desktop (example. Root)  
4. [Computer] Copy all Pre-Requesting files on it.  
5. [Computer] Launch **TWRP Installer**  
6. [Computer] If you get an alert that **Device Connected!** then maintain below instructions to complete Install TWRP.  
If you get **Device is not connected!!** alert then check device driver, make sure that device driver is properly installed into your PC and USB Debugging (ADB) is turned on.  
7. [Device] Now your Phone will be restart automatically and it will open TeamWin Recovery Project into your device. [Not Showing?](#fail-to-install-twrp)  
8. [Computer] Now open **Computer** and copy **SuperSU.zip** from your desktop folder to Device's Root Directory.  
9. [Device] Click on the Install Button, Select **SuperSU.zip** and then Slide to Flash it into your Device.  
10. Now unplug Device from your PC.  
11. [Device] By Default your Device will be restart several times then it will boot normally. [Device isn't booting?](#device-fail-to-boot-after-flashing-supersu)  
12. [Device] If you see **SuperSU** in the Application list then your Device is successfully rooted. [Not a System App?](#install-supersu-as-a-system-app)  

***Warning: If you do anything wrong then you will lose all of your data. So take a backup before flashing SuperSU.***


## How to find a device driver?
Before doing anything you need to download and install Device driver into your PC.  

Sometimes Android includes device drivers and sometime not. So we need to manually download USB drivers.  
You will not find your usb drivers into a specific website, you need to find it into search engine  
Just search into your Preferred Search Engine (I recommend Microsoft Bing) by typing **Usb Drivers for [Device name]**. Then open a website and download usb driver.  


## Fail to Install TWRP
Most of New devices doesn't allowed to installed custom Recovery. So the problem happens. If you still this error then you can use below steps  
Force stop TWRP installer  
Reboot PC and Mobile Device  
Unlock Bootloader of Android  
Restart the Installer


## Device fail to boot after flashing SuperSU
Sometime Device fail to boot after flashing SuperSU.zip. It happens if your SuperSU.zip goes corrupt. You need to download a fresh copy of SuperSU.zip from [here](#pre-requesting) and need to copy the file again into your device root directory and install it again.


## Install SuperSU as a System App
Sometime SuperSU installed like a User Application, It means you can easily uninstall SuperSU from your device from setting. For Preventing this, you need to install SuperSU as System App.  

Install [/system/app mover](https://play.google.com/store/apps/details?id=de.j4velin.systemappmover) into your Device.  
Click on the **SuperSU** from the list and restart your Device.

# Donation
If you like my work then you can support me by donating into following addresses.
### BTC : bc1qegx9kwdln6ch3cxl39as3k3ezxu6rrg2533vnq

# Contact
If you are interested then you can join into our telegram group [@techsouls0](https://t.me/techsouls0) or channel [@tecsouls](https://t.me/tecsouls)
