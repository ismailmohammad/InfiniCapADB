<h1 align="center">InfiniCapADB</h1>
<h2 align="center">Infinite ADB Screenshot Capture for Android™</h2>
<div align="center"><img src = "https://raw.githubusercontent.com/ismailmohammad/InfiniCapADB/master/InfiniCapADB_icon.png")/></div>

# Filename: InfiniCapADB
Author: Mohammad Ismail<br />
Version: 1.0.0<br />
Date: March 25, 2017<br />
Last Updated: March 25, 2017 <r>
Description: This Script uses the Android Debug Bridge (ADB) over
USB at the moment to take an initial Screenshot(Screen Capture) and then
requires the user to press the "Enter" key to continue with the screenshot
process. This is the initial release, very simple code for the time being.<br />

The format of the files generated utilize the date and time of the screenshot
being taken in the following format, date followed by time:
MM-DD-YYYY-HH-MM-SS.SS.PNG
where initial MM = Month, DD = Day, YYYY = Year, HH = Hour (24H Format),
Second MM = Minutes, SS.SS = Second (including Partial Seconds).
The script will first use ADB to create a directory called
"InfiniCapADB" at the root of the SD card and then proceed to take the initial
screenshot. ADB errors that arise shall be output to the screen.<br />
Compiled with Bat to Exe Converter Portable<br />
http://download.cnet.com/Bat-To-Exe-Converter-Portable/3000-2069_4-10555897.html<br />

# Requirements:
Android Debug Bridge(ADB) from SDK (or) Minimal ADB and Fastboot<br />
Device Specific Android ADB Drivers<br />
USB Debugging enabled on Device<br />
Android 4.0+<br />

# Instructions: (Important)
1.Download the InfiniCapADB.exe application or the InfiniCapADB.bat as a Batch File<br />
2.Place the .exe or the compiled .bat file in the same directory as the ADB<br />
Say the adb.exe is located at C:\Program Files (x86)\Minimal ADB and Fastboot\adb.exe,<br />
then the InfiniCapADB.exe or InfiniCapADB.bat should also be placed alongside that for it to work<br />
3. Run the Script and Enjoy!<br />

# Downloads:
Android Studio: <br />
https://developer.android.com/studio/index.html<br />
(OR)
Minimal ADB and Fastboot (XDA Link):<br />
https://forum.xda-developers.com/showthread.php?t=2317790

# DISCLAIMER:
This Batch File Script should not in anyway be misused or abused in
any way that goes against any existing policies. I will not be held liable for
your individual actions and I do not condone any harmful actions done with the
use of this code. Please read through all the documentation of the program as
I am not liable for any risks/damages that<br />
may incur due to direct and/or indirect usage of this program including but not
limited to data loss, thermal meltdowns, or being overrun with animal GIFs.
Also, please make sure you have all relevant important files saved and backed
up prior to using script.<br />

Resources Consulted:<br />
http://stackoverflow.com/questions/1642677/
generate-unique-file-name-with-timestamp-in-batch-script
