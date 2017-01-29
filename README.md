# Pixel Launcher Icons Mod
#### A modded version of Pixel Launcher Icons that includes many more of Google's round icons.

## Installation

NB: I would love to publish this modded version on Google Play, but it uses the same package name as the original so that Pixel Launcher can use it. Please install it manually, as described below.

1. Download the APK or source code from the [releases page.](https://github.com/ZeevoX/PixelLauncherIcons/releases)
2. Perform one of the following:
   - Copy the APK file to the phone and run it
   - Use ADB and run the following command from the folder where:<br>
      On Mac or Linux:<br>
      `cp apk-name.apk \SDK_LOCATION\platform-tools\`<br>
      `cd \SDK_LOCATION\platform-tools\`<br>
      `./adb install apk-name.apk`<br>
      On Windows<br>
         `copy apk-name.apk \SDK_LOCATION\platform-tools\apk-name.apk`<br>
         `cd \SDK_LOCATION\platform-tools\`<br>
         `adb install apk-name.apk`<br>
   - Build manually from source code by running the following command:<br>
      On Mac or Linux:<br>
      `./adb install apk-name.apk`<br>
      On Windows<br>
      `adb install apk-name.apk`<br>
3. Clear the data of Pixel Launcher to (re)enable the APK.
4. Enjoy!
