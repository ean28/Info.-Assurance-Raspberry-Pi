# Information Assurance and Security - Final Project

## BSCS 3A

**Group 6 Members**
* Aguilar, Troy
* De las Llagas, Gian
* Labios, Justine Dela Justa
* Subiera, Earl Krans
---
## Documentation

## 1. Headless Rapbian OS in Raspberry Pi Installation

* Insert the SD card reader equipped with the SD Card that you'll use and run the Raspberry Pi Imager.
    - Choose **Raspberry Pi 3** for Raspberry Pi Device, ***Raspberry Pi OS (Legacy)** for Operating System, and for storage choose the SD Card you inserted.
![1 1](<assets/images/Screenshot 2023-12-14 135727.png>)

> [!WARNING]
> Before proceeding make sure to backup all the important files on your card.

* In **GENERAL**, configure the following:
    - Set the Hostname
    - Set the Username and Password
    - Set the SSID and Password
    > Do not change the password of the wireless LAN
    - Set the Wireless Lan country
    - Set the Timezone
    - Hit save.
    
![1 2](<assets/images/Screenshot 2023-12-14 135839.png>)

* Apply the customisation setting erase all existing data on the selected SD Card. Click **Yes**.
![1 3](<assets/images/Screenshot 2023-12-14 135916.png>)

* Wait for the imager to write the OS to your SD card to finish.

## 2. Connect to Raspberry Pi with SSH using the terminal

* Connect to the SSH with ***ssh "<hostname>"@"<IP_Address>"***
![1 4](<assets/images/Screenshot 2023-12-14 144010.png>)