# MacOS Application from .SH


## What's this?
Mac-AppfromSH is a GitHub repository which allows you to make a Mac application [.app] from an SH [.sh] file
### .sh TO .app

## Installation/Usage

### Usage with code installation [Recommended]

Step 1: Download this repository and extract the ZIP
Step 2: Rename "Example App" to your app name. Then, right-click “Example App”, and click Show Package Contents
Step 3: Open “Contents”, info.plist and replace all “REPLACESTRING”s with your details
Step 4: Open “MacOS”, and edit main.command and replace all “REPLACESTRING”s with your details
Step 5: Replace “# Insert shell script code” with your code
Step 6: Open “Resources”, and replace app.icns with your logo [It must be an ICNS file and it must be called “app.icns”]
Step 7: Open Terminal and CD into the MacOS folder
Step 8: Run the following command: “chmod u+x main.command”
Step 9: Drag your application to /Applications
Step 10: Launch your application!
