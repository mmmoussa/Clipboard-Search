# Google-Clipboard

Google Clipboard allows you to quickly make yourslef a useful shortcut on your Mac. Google Clipboard allows you to designate a keyboard shortcut that will perform a Google Search in Safari, Firefox, or Google Chrome of whatever is stored in your clipboard (what you copied last). 

To use Google Clipboard, follow the following steps:
1. Go into the Automator program and make a new document.
2. Select "Service" as the type, and then under Library -> Utilities, choose "Run AppleScript".
3. Change "Service receives selected" to "no input". 
4. Copy the correct script from this repository as a replacement to the code provided as a placeholder.
5. Save the service.
6. Under System Preferences -> Keyboard -> Shortcuts, select "Services".
7. Choose the service you just created and assign it a shortcut.
8. Go ahead and use that shortcut!
