# MacOS Application from .SH


## What's this?
Mac-AppfromSH is a GitHub repository which allows you to make a Mac application [.app] from an SH [.sh] file
### .sh TO .app

## Installation/Usage

### Usage with code installation [Recommended]

Step 1: Download the latest release [Application Template] and extract ExampleApp.app.zip

Step 2: Rename "ExampleApp.app" to your app name. Then, right-click the app, and click Show Package Contents

Step 3: Open “Contents”, info.plist and replace all “REPLACESTRING”s with your details

Step 4: Open “MacOS”, and edit main.command and replace all “REPLACESTRING”s with your details

Step 5: Replace “# Insert shell script code” with your code

Step 6: Open “Resources”, and replace app.icns with your logo [It must be an ICNS file and it must be called “app.icns”]

Step 7: Open Terminal and CD into the MacOS folder of your application

Step 8: Run the following command: “chmod u+x main.command”

Step 9: Drag your application to /Applications

Step 10: Launch your application!

## Troubleshooting
### When launching your app, you might get the following error - "Cannot be opened because it is from an unidentified developer"
### In order to resolve this issue, complete the instructions below:

Step 1: Open System Preferences

Step 2: Click "Security & Privacy"

Step 3: Go to the "General" tab

Step 4: Click "Open Anyway"

Step 5: Click "Open" on the popup
