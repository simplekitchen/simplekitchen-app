# simplekitchen-app

Instructions and simple commands for running a development version of the app in Android and iOS are provided
Andriod
 1. Goto -> Settings -> About Device -> softwareInfo -> buildnumber(Click multiple times on Build Number to Enable Developer Options)
 2. search for Developer options
 3. Enable USB Debugging Mode
 4. open Android SDK Manger -> Platform Tools on terminal
 5. Write command adb devices
 6. start npm
 7. write command adb reverse tcp:8081 tcp:8081
