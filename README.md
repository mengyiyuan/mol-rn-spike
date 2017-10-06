
Things to notice:
* Before running start:ios or start:android, make sure to start the packager by running `npm start`
* Android Debug Bridge (adb) needs to be installed, follow the instructions at https://developer.android.com/studio/command-line/adb.html
  * Make sure the path to adb is added to PATH
  * an emulator/android device needs to be running/plugged in for the app to be successfully installed
* Please do not run `start:ios` and `start:android` together, because both will clear artifacts rebuild the app, it may break the other version which is watching changes
