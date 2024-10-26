# Guide-Installing-Ubuntu
Learn how to set up Ubuntu on your system with this step-by-step guide.

[1. Ubuntu system requirements](#1-ubuntu-system-requirements)

[2. Getting ready to install Ubuntu](#2-getting-ready-to-install-ubuntu)

[3. Ubuntu Setup](#3-ubuntu-setup)

[4. Installing Ubuntu 24.04](#4-installing-ubuntu-2404)

[5. Closing Remarks](#5-closing-remarks)


## 4. Installing Ubuntu

## 1. Ubuntu system requirements
To run Ubuntu effectively, you need a laptop or PC with at least 25 GB of storage space, a 2 GHz dual-core processor, and at least 4 GB of RAM, along with an 8 GB USB flash drive for creating the installation media and a stable internet connection for downloading updates and additional software. For a smoother experience, the recommended specifications include a 2 GHz quad-core processor or better, 8 GB or more of RAM, at least 25 GB of free space (ideally 50 GB or more), a graphics card that supports 3D acceleration, and a display with a resolution of at least 1366x768. Additionally, ensure that your hardware components (such as Wi-Fi adapters and printers) have Linux drivers available, and if your computer uses UEFI firmware, make sure it is configured correctly for Ubuntu installation. If you plan to dual-boot with another operating system, ensure you have sufficient disk space and a compatible partitioning setup.

## 2. Getting ready to install Ubuntu
### 2.1 Installing the image
First thing you need to this installing the image from ubuntu [website](https://ubuntu.com/download/desktop).
![1](https://github.com/user-attachments/assets/3db32a16-56cf-4dc4-9b5d-7b20262f4903)

### 2.2 Installing Rufus
After you downloaded the iso file it needs to be written to an installation medium, such as a flash drive. You can utilize the Etcher or Unetbootin utilities to create a bootable Linux flash drive. If you're using Windows, the [Rufus](https://rufus.ie/en/) utility is a great option for writing the image to the flash drive.
![2](https://github.com/user-attachments/assets/f9c34433-6648-4558-aa12-1eceb6233097)


### 2.3 Creating a Bootable USB Drive with Rufus
Once Rufus is downloaded, launch the application. You will see an interface where you can select your USB flash drive from the dropdown menu. Make sure to choose the correct drive to avoid data loss. Next, select the ISO image you downloaded earlier. After that, click the "Start" button to begin the process of creating the bootable USB drive. Follow any prompts that appear to complete the setup, and once finished, your USB drive will be ready for the Ubuntu installation.

![3](https://github.com/user-attachments/assets/1c44c9af-34e3-43cf-ab3c-7e331f68d249)

### 2.4 Accessing BIOS and Setting the USB Drive as the First Boot Option
Once the bootable USB drive has been created using Rufus, the next step is to access the BIOS setup. Restart your computer and during the boot process, press the designated key to enter the BIOS menu (common keys include F2, F10, F12, or Del, depending on your system). In the BIOS settings, locate the boot order options and set the USB drive as the first boot device.
After making these changes, save your settings and exit the BIOS. Your computer will now boot from the USB drive, allowing you to start the Ubuntu installation process.

![set-the-usb-flash-drive-as-the-first-bootable-option](https://github.com/user-attachments/assets/83ad0c96-6a04-40fc-8874-a8a5ca55ef2f)

## 3. Ubuntu Setup
After configuring the BIOS settings, restart your computer, and if the USB drive is set correctly (if not refer to this [guide](https://helpdeskgeek.com/how-to/how-to-change-the-boot-order-in-the-bios-on-your-windows-pc), it should boot from the USB, bringing up the Ubuntu installation screen. 
### 3.1 Selecting language 
Here select your preferred language and click "Next".

![lng](https://github.com/user-attachments/assets/9e82e40f-4688-49df-b64d-feed07d82345)

### 3.2 Selecting keyboard layout
Then, select your keyboard layout and click "Next" again. You may be prompted to choose between different keyboard options; simply select the one that matches your preference.

![kyb](https://github.com/user-attachments/assets/69bab95f-bfcd-441e-83b6-f11fa1335f11)

### 3.3 Connecting to Wi-Fi
Next connect to wi-fi, if you do connect to the internet you can do things like downloading updates
while installing which will save your time after the installation is finished.

![wifi](https://github.com/user-attachments/assets/aa89f2b5-e8fd-4727-a036-006a5c42a126)

## 4. Installing Ubuntu 24.04
After that click "Install Ubuntu".


![insub](https://github.com/user-attachments/assets/9f8adf42-2eeb-4d68-9b1d-6ca7fc34e273)


Then click "Interactive installation".

![inter](https://github.com/user-attachments/assets/41828266-5f96-43d7-940c-3963c33eb6aa)



![def](https://github.com/user-attachments/assets/35c7e17c-b3b7-451b-ae91-7021ec31835f)

Here extended selection generally offers more options and flexibility, while default selection provides a simpler and more user-friendly experience. If you’re a beginner and prefer a less complicated approach, default selection might be the friendlier option. However, if you want more control and options, extended selection can be a good choice. Ultimately, it depends on the user experience; for newcomers, default selection may be more suitable.


### 4.1 Disk setup

![part](https://github.com/user-attachments/assets/a9302881-4561-42c8-ae56-93889ab9c0ec)

This screen provides three options: installing Ubuntu alongside an existing OS, erasing the disk to install Ubuntu from scratch, and a manual installation for advanced users to customize partitions. I recommend choosing the "Erase disk and install Ubuntu" option, as this will completely remove all existing data on the disk before installing Ubuntu. After selecting your preferred option click "Next".

### 4.2 Creating account
After that create your account.

![acc](https://github.com/user-attachments/assets/17a8897e-66f6-4299-9322-804c31b90953)

### 4.3 Selecting timezone
Select ur timezone here.

![IMG-20241026-WA0037](https://github.com/user-attachments/assets/b29f5363-4dc2-4253-8d68-9c90e009198c)

### 4.3 Review your choices
You should take a look at this carefully once again.
Then click "Install".

![rewiev](https://github.com/user-attachments/assets/771b02ef-4e9c-4181-bdf4-31f740c5b243)

### 4.4 Restarting PC
After the ubuntu is installed restart your PC.

![reset](https://github.com/user-attachments/assets/78cbea36-43c5-4c43-82e1-ace43a4eca30)

### 4.5 Removing USB flash drive
After rebooting your PC you can remove your USB flash drive and press "Enter".

![remove](https://github.com/user-attachments/assets/0aaf30eb-e81e-44e6-a2ab-77629fee1537)

## 5. Closing Remarks
Well done! Now explore the Ubuntu desktop environment and start personalizing your system. Ubuntu offers a wide range of applications, tools, and customization options that cater to different user needs, whether for personal use, development, or professional work. Remember to update your system regularly to keep it secure and take advantage of the latest features. Enjoy your new Ubuntu experience and welcome to the world of open-source!
