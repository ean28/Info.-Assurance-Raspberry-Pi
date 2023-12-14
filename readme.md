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

* Run the following commands:

    - ***ssh "hostname@IP_Address"***
    ![2 1](<assets/images/Screenshot 2023-12-14 144010.png>)

    - ***sudo apt update***
    ![2 2](<assets/images/Screenshot 2023-12-14 144035.png>)

## 3. Deploy Linux Apache MySQL PHP (LAMP Stack) in Raspberry Pi

* Run the following commands:
    - ***sudo apt install apache2***
    ![3 1](<assets/images/Screenshot 2023-12-14 150005.png>)
    
    - ***sudo apt install mariadb-server***
    ![3 2](<assets/images/Screenshot 2023-12-14 150042.png>)

    - ***sudo mysql_secure_installation***
    ![3 3](<assets/images/Screenshot 2023-12-14 144212.png>)

    - ***sudo apt install php libache2-mod-php php-mysql***
    ![3 4](<assets/images/Screenshot 2023-12-14 144056.png>)

    - ***sudo apt-get install php***
    ![3 5](<assets/images/Screenshot 2023-12-14 145750.png>)

    - ***sudo apt install phpmyadmin***
    ![3 6](<assets/images/Screenshot 2023-12-14 144056.png>)

* You have now successfully installed and deployed LAMP Stack in Raspberry Pi

## 4. Installation of RealVNC and Controlling Raspberry Pi

* Download and install [RealVNC](https://www.realvnc.com/en/connect/download/viewer/) on your computer.

    - Click Next.

    ![4 1](<assets/images/Screenshot 2023-12-14 141039.png>)

    - Accept the terms and agreement.

    ![4 2](<assets/images/Screenshot 2023-12-14 141058.png>)

    - Click Next

    ![4 3](<assets/images/Screenshot 2023-12-14 141115.png>)

    - Tick the checkbox to add RealVNC to Firewall exemptions, and click Next.

    ![4 4](<assets/images/Screenshot 2023-12-14 141128.png>)

    - Install.
    
    ![4 5](<assets/images/Screenshot 2023-12-14 141139.png>)

* Follow the installation procedures. After that, when you are prompted to select the main web server to run phpMyAdmin, choose **apache2**. 
![4 6](<assets/images/Screenshot 2023-12-14 150503.png>)

* Once RealVNC Reviewer opens up, type in your IP Address.
![4 7](<assets/images/Screenshot 2023-12-14 151738.png>)

* Done.
![4 8](<assets/images/Screenshot 2023-12-14 152013.png>)