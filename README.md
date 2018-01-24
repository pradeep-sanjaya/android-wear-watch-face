# android-wear-watch-face
Android wear watch face for android wear 2.8, android 7.1.1

#### Enable Developer Options in Phone
Settings > About device > Build number
Once you’ve found the Build number section of the settings, tap on the section 7 times.

#### Enable Developer Options in Wear Device
Setting > System > About > Build number
Once you’ve found the Build number section of the settings, tap on the section 7 times.

#### Enable USB Debuging on Phone

#### Enable Wi-Fi Debuging on Wear Device
Settings > Developer options > Adb debuging
Settings > Developer options > Debug over Wi-Fi (IP Address:Port)

#### Enable Wi-Fi in Phone

#### Enable Wi-Fi in Wear Device

#### Find the IP address of the Phone
Settings > Wi-Fi > Connected Wi-Fi > IP Address
Ex: 192.168.1.3

#### Find the IP address of the Wear Device
Settings > Connectivity > Wi-Fi > Connected Wi-Fi > IP Address
Ex: 192.168.1.4

## ADB
#### Locate Android SDK platform tools
/home/user/Android/Sdk/platform-tools

#### Connect to Phone from ADB over TCP
./adb tcpip 5555
./adb connect 192.168.1.3:5555

#### Connect to Wear Device from ADB over TCP
./adb connect 192.168.1.4:5555

#### List Connected Devices from ADB
./adb devices

#### Install APK to Wear Device from ADB over TCP
./adb -s 192.168.1.4:5555 install <application.apk>
