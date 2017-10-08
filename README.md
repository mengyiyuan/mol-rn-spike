# React-Native with TypeScript Boilerplate
By following the tutorial at [react-native-with-typescript](https://medium.com/@rintoj/react-native-with-typescript-40355a90a5d7) with some changes due to react-native CLI updates

## To package the app
```
npm start
```

## To run packaged app in respective emulators
* On IOS, run `npm run start:ios`
* On Android, run `npm run start:android`

## Things to notice:
* Android Debug Bridge (adb) needs to be installed before running android app, follow the instructions at https://developer.android.com/studio/command-line/adb.html
  * Make sure the path to adb is added to PATH
  * an emulator/android device needs to be running/plugged in for the app to be successfully installed
* Please do not run `start:ios` and `start:android` together, because both will clear artifacts rebuild the app, it may break the other version which is watching changes

## Things different from tutorial
* react-native CLI no longer generates two super similar index.ios/android.js, but just one single index.js
