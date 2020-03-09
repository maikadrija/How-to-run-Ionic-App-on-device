# How-to-run-Ionic-App-on-device
How to run Ionic App on Android and iOS 

## iOS

1. $ ionic cordova prepare ios

2. *Open the main config.xml file and modify the id attribute of the root element, <widget>.*

3. $ cordova plugin save && cordova platform rm ios && cordova platform add ios

4. $ ionic cordova prepare ios

5. *Open Xcode. Use **File** » **Open** and locate the app. Open the app's platforms/ios directory.*

6. *Define the Developer Team for the App*

7. *Choose Simulator or connect iPhone to Mac and press run*

Note: After changes to the app you have to rerun this command: * $ ionic cordova prepare ios *



## Android

1. $ ionic cordova prepare android

2. *Enable developer options on Android Device*

3. *Enable USB debugging on Andorid Debvice*

4. *Accept USB debugging on phone for laptop*

2. *Open the config.xml file and modify the id attribute of the root element, <widget>.*

3. *Start the Android Simulator or connect Android Device to Computer.*

4. $ ionic cordova run android -l




**********************
 
https://ionicframework.com/docs/building/ios
https://ionicframework.com/docs/building/android

