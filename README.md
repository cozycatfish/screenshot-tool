# screenshot-tool

A small screenshot tool for OS X.

Instructions:

1. Select the type of screenshot to take (or press return for a fullscreen one)
2. Select the window to take (if capturing a window screenshot)
3. There is no step 3.

It saves to the Downloads folder by default as a PNG with the date as the filename.
Unlike Grab or other screenshots apps it doesn't show its icon in the dock giving clean screenshots.

Unfortunately, the folder in which the screenshots are saved is hardcoded. To change it, open the app in Applescript.

Saving the app afterwards will then lead to the app icon being shown in the dock. To hide the app icon while running, open the Info.plist and add the following string right before the second to last ` </dict>` element:

`<key>LSUIElement</key>`

`<true/>`

This is licensed under a MIT license.
