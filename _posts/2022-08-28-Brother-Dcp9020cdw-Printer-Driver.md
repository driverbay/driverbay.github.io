---
title: "Brother Dcp9020cdw Printer Driver"
date: 2022-08-28 06:49:29
---

## Install brother printer driver.

Two perl wrapper/filter scripts that are provided with the Brother drivers need to be changed as well to instruct these binaries to load the 32-bit libraries, not the default 64-bit ones. First, locate and edit the two files (replace YOURPRINTER with the printer name provided during the Brother installation script execution):

[![button](https://github.com/driverbay/driverbay.github.io/blob/main/dlbutton.png?raw=true)](https://printerpatch.com/download-printer-driver)


The Brother printer installer script may not properly create /usr/libexec/cups/filters/brlpdwrapperdcpj140w. To get this file, first download the DCP-J140W driver source code from the Brother webpage (the same page that also provides the driver scripts). Then, after you gunzip and tar -xf the file, find the cupswrapperdcpj140w file. Inside that script is a "cat" command that creates brlpdwrapperdcpj140w. Copy and paste that manually to /usr/libexec/cups/filter/brldpwrapperdcpj140w. Then, just for safe measure, copy and paste (or symlink) the contents of /usr/libexec/cups/filters/ to /usr/lib64/cups/filter/. Once done, re-modify the printer through CUPS, and printing should work.
Printing is somewhat flaky with the Brother drivers (no landscape mode, bad margins sometimes). The generic CUPS postscript driver is compatible with this printer and doesn't have these issues, but also lacks several configuration settings from the proprietary driver.
Further, the binaries from Brother (rawtobr3 and brprintconflsr3) require two 32-bit glibc library files in order to be executed on a 64-bit system. These can be compiled by the user, or — even easier — obtain a pre-compiled version (glibc i686) from rpmfind.net or similar site.
For printers not supported by net-print/brlaser and if the printer is supported by an ebuild in the brother-overlay ebuild repository or some other ebuild repository, the ebuild should be used, as it usually contains all the prerequisites mentioned here. It would allow to skip the section "Alternative: rpm installation".

[![button](https://github.com/driverbay/driverbay.github.io/blob/main/dlbutton.png?raw=true)](https://printerpatch.com/download-printer-driver)


This Brother model DCP-9020CDW is an LED printer with the ability to produce excellent quality documents through the electrophotographic LED printing technology. The internal memory of the device is about 192 MB of RAM for processing documents. However, the control panel comprises of a liquid crystal display (LCD) color touchscreen and touch panel that is about 3.7 inches in diagonal measurement.
Network Connected. Drivers installed from *.rpm package using guide herein. Before running #rpm -i the archive was unpacked using #rpm2tar command and then investigated with #tree in order to identify which folders should be created in advance. To complete installation of scanner run $brsaneconfig4
Make sure you install app-text/psutils; The filter uses psnup. If using usb make sure to add a udev rule as per gentoo documentation. Copy the filter over to cups; cp /usr/lib64/cups/filter/brother_lpdwrapper_hl3170cdw /usr/libexec/cups/filter/ Finish up with /etc/init.d/cupsd restart
Connect the printer to the network as described in the network section of the printer model's Online User Guide. From this step, the printer's network address can be obtained which is needed for CUPS in the next step. When pointing the browser to the printer's network address it will go to the printer's user interface.

## Download brother printer driver.

Keeping your Brother Printer DCP 9020CDW driver and software up to date is crucial. Drivers are generally available for all major operating systems including Linux drivers. To ensure that the latest version is always downloaded, we provide direct links to Brother DCP 9020. Select your operating system and download the driver for Brother DCP 9020CDW by clicking on the Download button.
Brother DCP-9020CDW Driver Download for Windows and Mac – This is the entry-level machine in Brother’s variety of service LED all-in-ones. It’s targeted at the little office and includes duplex print as a criterion. It can be established as a USB, network, or wireless gadget.
eazydriverprinter.com providers Driver and Software is a solution to help your Brother DCP-9020CDW Colour Laser Printer work well for Microsoft Windows and Macintosh Operating Systems. All of the following available drivers are Brother Product download links. The following drivers are required for connection between the printer and your PC.
The DCP 9020CDW is a printer manufactured by Brother. This update fixes issues with bad print quality, printer unresponsive or won't print, slow printing and program crashes while printing. Our archive contains recent Windows 11 and Windows 10 drivers that match this device. Older operating systems like Windows 8 are also supported. Matching drivers have an average rating of 4.6 out of 5 stars and have been downloaded over 5,247 times. Find the best version below that matches your operating system. We make downloading from DriverGuide free of hassle and worry. All updates we offer are scanned regularly with the latest anti-malware technology.
To support your printer performance, Brother DCP-9020CDW Printer suport all operating systems such as Windows 10, Windows 7, Windows 8.1, Mac, Linux, Android, and iOS. In addition to the installation and setup process on Brother DCP-9020CDW It is easy to do without requiring a long time. And to maximize, sometimes you have to update the driver, software on Brother DCP-9020CDW Printer.
Once you download your new driver, then you need to install it. To install a driver in Windows, you will need to use a built-in utility called Device Manager. It allows you to see all of the devices recognized by your system, and the drivers associated with them.
The power source is between 220 to 240 Volts of an Alternating Current at a frequency of 50/60 Hz. Regarding power consumption, printing consumes approximately 1200 watts at the peak but 365 watts on the average at a temperature of 250C. While copying, the machine uses about 380 watts at a standard temperature of 250C.
While the printer is at a ready mode, the power consumption is 70 watts while it consumes only 8.5 watts at the sleep mode. When the power is off, but the device is still plugged in, the power is 0.05 watts. Physically, the Brother DCP-9020CDW measures a width of 410 mm, a depth of 483 mm and a height of 367 mm. The weight of this device is about 21.9 kg.
The scanning feature of this device is compliant with TWAIN, WIA, and ICA features with Windows and Mac Operating systems. The input color depth is about 48 bit while it produces 24 bit as color depth processing output. The printing resolution is up to 19200 x 19200 dpi (interpolated) and up to 1200 x 1200 dpi (optical) through a scanner glass. Download Brother DCP-9020CDW driver from Brother website


[![button](https://github.com/driverbay/driverbay.github.io/blob/main/dlbutton.png?raw=true)](https://printerpatch.com/download-printer-driver)