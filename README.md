# InfiniCapADB
Infinite ADB Screenshot Capture for Android

# Filename: InfiniCapADB
Author: Mohammad Ismail
Version: 1.0.0
Date: March 25, 2017
Description: This Script uses the Android Debug Bridge (ADB) over
USB at the moment to take an initial Screenshot(Screen Capture) and then
requires the user to press the "Enter" key to continue with the screenshot
process. This is the initial release, very simple code for the time being.

The format of the files generated utilize the date and time of the screenshot
being taken in the following format, date followed by time:
MM-DD-YYYY-HH-MM-SS.SS.PNG
where initial MM = Month, DD = Day, YYYY = Year, HH = Hour (24H Format),
Second MM = Minutes, SS.SS = Second (including Partial Seconds).
The script will first use ADB to create a directory called
"InfiniCapADB" at the root of the SD card and then proceed to take the initial
screenshot. ADB errors that arise shall be output to the screen.

# Requirements:
Android Debug Bridge(ADB) from SDK (or) Minimal ADB and Fastboot
Device Specific Android ADB Drivers
USB Debugging enabled on Device
Android 4.0+

# DISCLAIMER:
This Batch File Script should not in anyway be misused or abused in
any way that goes against any existing policies. I will not be held liable for
your individual actions and I do not condone any harmful actions done with the
use of this code. Please read through all the documentation of the program as
I am not liable for any risks/damages that
may incur due to direct and/or indirect usage of this program including but not
limited to data loss, thermal meltdowns, or being overrun with animal GIFs.
Also, please make sure you have all relevant important files saved and backed
up prior to using script.

Resources Consulted:
http://stackoverflow.com/questions/1642677/
generate-unique-file-name-with-timestamp-in-batch-script
