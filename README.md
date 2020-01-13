# AutoInstaller
Asset store link: http://u3d.as/1zwk

Auto Install tool for Unity3d. It will automaticly install apks via wifi to your device after build.

## Requirements
- Android SDK installed and set in Unity preferences
- Android device with Developer options enabled
- “USB Debugging” and "Install via USB" options enabled

## Installation
- Import Auto Installer package from Unity Asset Store
- Click **Tools/AutoInstaller/Configuration** menu option
- Connect your android device via USB to computer
- Click on **Register connected device**
- Check **Always allow from this computer** on your device screen and press OK
- (optional) You can set name to your device in **Registered Devices** list
- Make sure that **Target device** was set and **Install after build** toggle is on
- Go to **Build Settings** and press **Build**

*After successful build new apk will be installed on your device.*

## Additional features
- **Tools / Auto Installer / Install Last Build** - Install last successful build to your current target device.
- **Tools / Auto Installer / Launch app on device** - Connect to current target device and Start your app if it installed.
- If you have multiple devices to test your builds, you can add as many as you want and switch between them in AutoInstall config file.

## Feedback or support
If you have any questions, suggestions or comments, please contact me by email (zimennik@gmail.com)
