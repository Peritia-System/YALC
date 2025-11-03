Linux# **Installing the Operating System**

Follow the steps below to install Linux from your bootable USB drive or mounted ISO file.

---

## Steps

1. **Insert the installation media**

	* For a physical computer: Plug in the bootable USB drive you created earlier.
	* For a virtual machine (e.g., VirtualBox, VMware, Hyper-V): Mount the ISO file as the virtual CD/DVD drive.


2. **Boot from the installation media**

	* Restart your computer or start the virtual machine.
	* Access the **boot menu** by pressing the appropriate key during startup (commonly **F12**, **F9**, **F2**, or **Esc**; check your manufacturer’s website for details).
		* Refer to the [Known BIOS Keys](../_Other/Bios_Key.md) document for a list of boot and BIOS access keys.
		* If you are aware of additional keys not listed, please contribute by adding them to the file for future reference.
	* Select your USB drive or mounted ISO as the boot device.

3. **Choose “Start Fedora-Xfce-Live”**

	* Wait for the system to load into the Fedora Live environment.
	* You can try Fedora without installing it or proceed directly with the installation.

4. **Begin the installation**

	* On the desktop, double-click **Install to Hard Drive**.
	* The Fedora installer will open and guide you through selecting your language, keyboard layout, and time zone.

5. **Select the installation destination**

	* Choose the target drive (usually your internal hard drive or virtual disk).
	* If you are new to Linux, use the **Automatic** partitioning option.
	* Advanced users may choose **Custom** to configure partitions manually.

	**Important:** Selecting a drive and proceeding with installation will erase all existing data on that disk. Make sure you have backed up any important files.

6. **Set up user and password information**

	* Create a root password and a regular user account with a secure password.
	* Before entering passwords or other details, confirm that the correct keyboard layout is selected.

		* Open the application launcher, search for “Keyboard,” and adjust the layout or variant if necessary.

7. **Start the installation**

	* Click **Begin Installation** and wait for the process to finish.
	* Installation time may vary depending on your system and storage speed.

8. **Reboot into the new system**

	* When installation completes, click **Finish Installation** and then **Reboot System**.
	* Remove the USB stick or unmount the ISO when prompted.

9. **Log in to Fedora**

	* After rebooting, log in with the user credentials you created during setup.
	* The system is now ready to use.
