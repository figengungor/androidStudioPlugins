# Android Studio Plugins


### [ADB Idea](https://github.com/pbreault/adb-idea)

Ctrl+Shift+A => 
Start typing adb and choose from many options (Uninstall app, clear app data, revoke permissions...)

### [OK, Gradle!](https://github.com/scana/ok-gradle)

Ctrl+Shift+A =>
Start typing ok, gradle and click on it. Type name of your library and get your dependency. 
### [Markdown Navigator](https://github.com/vsch/idea-multimarkdown)

Create a README.md file and get your preview. 

### [ButterknifeZelezny](https://github.com/avast/android-butterknife-zelezny)

Imagine you have a very long form layout and you use Butterknife. This plugin is a breeze in this case. 
It creates all the injections for you. I just had a great moment with it. It even gives option for OnClick. :tada


### Debug Your App Over Wi-Fi

1. Open terminal
2. Connect your device with usb cable, run ```adb devices``` to check if it is connected.
3. run ```adb tcpip 5555```
4. Disconnect your usb cable
5. Go to your device settings >> about phone >> network >> get ip address
6. run ```adb connect ip-address-inserted-here```
