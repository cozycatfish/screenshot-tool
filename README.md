# screenshot-tool

A small screenshot tool for OS X.

## Features

- Easy and fast. Grab requires choosing a place to save the screenshot, Screenshot Tool saves to the Downloads folder.
- Clean screenshots. Screenshot Tool gives no ugly dock icon.
- Saves screenshots as PNGs.

The folder in which the screenshots are saved is hardcoded. To change it, open the app in Applescript.

Saving the app afterwards will then lead to the app icon being shown in the dock. To hide the app icon while running, open the Info.plist and add the following two strings right before the second to last ` </dict>` element:

`<key>LSUIElement</key>`

`<true/>`

This is licensed under a MIT license.
