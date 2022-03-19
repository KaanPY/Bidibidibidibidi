# One Dark Arduino
Modern dark theme for the Arduino IDE, inspired by One Dark Pro for VSCode by binaryify: https://binaryify.github.io/OneDark-Pro/#/. Based on work done by Jeff Thompson: https://create.arduino.cc/projecthub/rahulkhanna/dark-theme-for-arduino-ide-17c001?ref=search&ref_id=theme&offset=0 

![screenshot](https://raw.githubusercontent.com/konrad91/OneDarkArduino/master/one_dark_arduino_1.png)

The following is credited to https://github.com/jeffThompson/DarkArduinoTheme 

### INSTALLATION  

* Mac users should look in `~/Applications/Arduino.app/Contents/Java/lib` and replace the `theme` folder inside (making a copy of the original in case want to revert back).  
* Windows is located in `C:\Program Files (x86)\Arduino\lib`.  
* Linux will be in `/usr/share/arduino/lib/`  

### CREATING YOUR OWN MODS
The newest version of the Arduino IDE makes creating custom themes trickier: you now need to edit the `theme.txt` file, an XML file inside the `syntax` folder, and the button files. Unfortunately, not all items in the `theme.txt` file actually work, so if you can't get an item to change, try another one of the files.

\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).

-------------------------------------------------

## Step 1: Downloading the One Dark Arduino theme
Go to https://github.com/konrad91/OneDarkArduino and download and the.zip-file.

## Step 2: Replace the "Theme" Folder
Go to the directory where Arduino is installed. The default directory is "C:\Program Files (x86)\Arduino\lib". Rename the original "theme" folder for backup. Then drag the "theme" folder from the.zip-file in.

![image](https://user-images.githubusercontent.com/77877967/159138176-d1be9b11-ec97-4f68-8db5-6ce0af1b302d.png)

## Step 3: Change Preferences.txt
Open the preferences.txt file for Arduino. The default location is C:\Users\USERNAME\AppData\Local\Arduino15. To help find it, you can also go into the Arduino IDE->File->Preferences and click the link on the bottom.

![image](https://user-images.githubusercontent.com/77877967/159138186-d454d0f9-57cf-4efa-bc1b-1682c87b327e.png)

Remeber to close the Arduino IDE before editing the preferences.txt!

Change the line that says "editor.font=..." to the following:

"editor.font=Consolas, plain, 14"

This will give the Arduino IDE a font that looks very similar to the One Dark Pro theme.

## Step 4: Enjoy Your New Dark IDE!
That is all, enjoy the new theme!

![image](https://user-images.githubusercontent.com/77877967/159138201-87ddac9a-23be-4634-994d-d336ab09d971.png)

# CODE
```C++
editor.font=Consolas, plain, 14
```
