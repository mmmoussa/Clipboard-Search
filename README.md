# :clipboard: Clipboard Search

Clipboard Search allows you to quickly make yourself useful shortcuts on your Mac for searching Google and Wikipedia. Clipboard Search allows you to designate keyboard shortcuts that will perform a Google or Wikipedia search in Safari, Firefox, or Google Chrome of whatever is stored in your clipboard (what you copied last). 

<br>
To setup Clipboard Search, follow the following steps:

1. Go into the *Automator* program and make a new document.
 
2. Select "Service" as the type, and then under *Library -> Utilities*, choose "Run AppleScript".

3. Decide whether you want to create a tool for searching Google or one for Wikipedia. 

4. Copy the correct script from this repository as a replacement to the code provided as a placeholder.

5. Save the service.

6. Under *System Preferences -> Keyboard -> Shortcuts*, select "Services".

7. Choose the service you just created and assign it a shortcut.

8. Go ahead and use that shortcut!

<br>
For Google search scripts, use the appropriate script under the Google folder of this repository, and for Wikipedia search, use the correct script in the Wikipedia folder.
