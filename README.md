# PSX 2.11 ReTranslated - English
English translation for the 2.11 XMB on the PSX (DVR). </br>

Tested on a PSX DESR-7500 with Firmware 2.11.

Based on: https://github.com/SvenGDK/PSX-English-Translation/releases

ReTranslation in progress by NallWolf

/!\This translation does overwrite some XML files that include strings not inside .dic files and/or needed positioning edits, please make and keep a backup of your packages folder before installing this translation./!\

The majority of this translation leverages Sony's own support of a hidden language setting. After installation, you will need to change the language setting to English using OSDMenu by pcm720 (https://github.com/pcm720/OSDMenu) before the XMB will show in English. This also means you can switch back to Japanese at any point and most of the XMB will be back to stock (except for stuff that was in XMLs).

### Installation
/!\Requires the ability to run wLaunchELF r3z (https://github.com/saildot4k/wLaunchELF_R3Z) and OSDMenu (https://github.com/pcm720/OSDMenu) /!\

0. MAKE SURE YOU HAVE A BACKUP OF YOUR PSX's STOCK xosd FOLDER BEFORE CONTINUING
1. Copy the folder "__system" to a FAT32 (MBR) formatted USB drive.
2. Start wLaunchELF on your PSX and go to "mass:/"
3. Open the folder "__system" and MARK both "dic" and "xosd" with cross (X)
4. Press R1 on your controller and select "Copy" from the list
5. Go back to the main menu and open "hdd:/"
6. Open now the folder "__system" and copy both folders in this directory with R1 -> "Paste"
7. Several overwrite popups will appear -> Confirm with "OK"
8. After everything has been copied, restart your console or press the "Quit game" button
9. Launch OSDMenu and change the language to English in System Configuration, then restart or press the "Quit Game" button
10. The system should be now in English
