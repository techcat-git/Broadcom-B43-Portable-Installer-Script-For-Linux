Portable Bash Script That Installs The Broadcom "B43" Driver for BCM43XX Wireless Network Cards On Linux. (No internet connection required.)

This script takes advantage of Base64 encoding to encode the driver files inside of the script, making it easier to install without an internet connection!

**Required packages: sudo, base64, unzip (these should be installed by default on most Linux distros. but if they aren't, you must install them before using this script.**)

(This script will NOT work on Adelie Linux or other distros that do not have the "modprobe" command.)

<img width="854" height="651" alt="image" src="https://github.com/user-attachments/assets/9762dbcf-6f30-485c-997e-18c0e6a385c2" />

How to use:

1. Download **"b43.sh"** from the repository and transfer it to the computer you'd like to install the b43 driver to.

2. Open a terminal and cd into the directory you have the script in, and make sure the script is set as executable by typing "chmod a+x b43.sh".

3. Run the script as root by typing "sudo ./b43.sh" and then follow the on screen instructions!

Tested machines:

✅ - iMac G5

✅ - Dell Latitude D610

✅ - Dell Inspiron 1720


