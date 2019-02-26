# AntiMicro

AntiMicro is a game controller key-mapper for Windows and Linux.




# Installing AntiMicro

**Windows Installation:**
Download the file for your architecture and run it.
For 64 Bit Systems: https://github.com/AntiMicro/antimicro/releases/download/2.21/antimicro-2.21-win64-fixedSDL.msi
For 32 Bit Systems: https://github.com/AntiMicro/antimicro/releases/download/2.22/antimicro-2.22-win32.msi
*Note: This repository is not managed by us and may be deleted.*

**Linux Installation:**

**1.** Make sure you have gdebi installed.
`sudo apt install gdebi`
**2.** Use Wget to download the apropriate file.
For 64 Bit systems: `wget https://github.com/ITCMD/AntiMicro/raw/master/antimicro_2.23~artful-1_amd64.deb`
For 32 Bit Systems: `wget https://github.com/ITCMD/AntiMicro/raw/master/antimicro_2.23~artful-1_i386.deb`
**3.** Install the software.
`sudo gdebi antimicro*.deb`
# Using AntiMicro
Now that you've installed it you can run antimicro from your launcher, or in the terminal by running `antimicro` on linux. Be sure to plug in your controller after the software has launched. It should look something like this for a regular controller (not a joystick):
![image](http://i.imgur.com/uBgNUwT.png)

**Now you can download or create some antimicro scripts to use!**
We have a collection that we designed for a classic rock candy usb controller.

# Aditional Info

**To Uninstall** run `sudo apt remove antimicro`. 

**Note:** You can find versions for other systems at https://pkgs.org/download/antimicro. We cannot verify the legitimacy of this website or it's downloads, as we do not have any alternative linux systems. If something does not work or includes malware let us know and we will take down the link.

*Disclaimer! AntiMicro is not designed or upkept by IT Command. It was abandoned in 2016, however the last versions run stable enough. We have copies of the linux version in case the main repository goes down. Original archive: https://github.com/AntiMicro/antimicro and https://github.com/AntiMicro/antimicro/releases*
