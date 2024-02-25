List all avaiable emulators
> emulator -list-avds

Run an emulator from command line: 
> export ANDROID_SDK=$HOME/Library/Android/sdk

> export PATH=$ANDROID_SDK/emulator:$ANDROID_SDK/tools:$PATH

> emulator -avd <<Pixel_7_Pro_API_30>> -netdelay none -netspeed full

Install an APK from commandline 
> adb install /Users/macbookpro/Desktop/easyPiano.apk
