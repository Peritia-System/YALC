# **Creating a Bootable Linux USB Drive (Windows Guide)**

This guide explains how to create a bootable USB drive that allows you to install or run Linux directly on your computer using Windows.

---

## Requirements

### Hardware

* A USB stick (8 GB or larger)

### Software

* A Linux image file (`.img` or `.iso`): [Fedora Xfce Spin](https://fedoraproject.org/spins/xfce)
* **Rufus**, a free tool for creating bootable USB drives: [Download Rufus](https://rufus.ie)

---

## Steps Overview

1. [Download the Linux Image](#1-download-the-linux-image)
2. [Download Rufus](#2-download-rufus)
3. [Create the Bootable USB Drive](#3-create-the-bootable-usb-drive)
4. [Boot from the USB Stick](#4-boot-from-the-usb-stick)

---

## 1. Download the Linux Image

1. Go to the official Fedora Spins website: [https://fedoraproject.org/spins/xfce](https://fedoraproject.org/spins/xfce)
2. Download the **Fedora Xfce 43 Live ISO** for Intel and AMD (x86_64) systems.
3. Alternatively, you can use the **BitTorrent** download option.
4. Save the ISO file to your **Downloads** folder — not to the USB stick.

---

## 2. Download Rufus

1. Visit the official Rufus website: [https://rufus.ie](https://rufus.ie)
2. Download the latest version of **Rufus for Windows**.
3. Save the file (`Rufus.exe`) to your **Downloads** folder.

**Note:** As of 2025, **balenaEtcher** is not recommended due to privacy concerns involving data sharing with the Balena company.

---

## 3. Create the Bootable USB Drive

1. **Open Rufus.**
	If prompted by Windows, click **Yes** to allow changes.
	If an “Update Policy” message appears, choose **No**.

2. **Insert your USB stick.**
	Be aware that all data on the USB stick will be erased.
	Avoid using a USB stick that contains important files.

3. **Select your USB device.**
	Under **Device**, choose the USB stick you inserted.
	If it doesn’t appear, make sure Rufus was not saved directly on that USB stick.

4. **Select the Linux image file.**
	Click **Select**, navigate to your **Downloads** folder, and choose the Linux ISO file you downloaded earlier (for example, `Fedora-Xfce-Live-x86_64-43.iso`).

5. **Start the process.**
	Click **Start**, confirm any prompts, and enter your Windows password if required.
	Rufus will write the Linux image to the USB stick. This process may take several minutes.

6. **Finish.**
	Once Rufus displays “Ready,” close the program.
	Your bootable Linux USB drive is now complete.


## For Existing Linux Users

If you already use Linux, you can create a bootable USB drive :) 
I Believe in you

Once you’ve completed the process once, repeating it is straightforward.
