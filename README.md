# BugFix-QBluetooth-pairing-pin

Created by E-Protocol
https://github.com/e-protocol

Bug fix: QBluetooth pairing pin failure with user input

Description: 
Includes QtBluetoothBroadcastReceiver (java) file - required for fixing bug 
with pairing devices with 4-digit pin (i.e. 0000/1234). Just follow the 
instructions below.

Instructions:
1) Download QtBluetoothBroadcastReceiver.java from GitHub
https://github.com/e-protocol/BugFix-QBluetooth-pairing-pin
2) Replace original file. In my Linux OS location:
/opt/Qt5.12.3/5.12.3/Src/qtconnectivity/src/android/bluetooth/src/org/qtproject/qt5/android/bluetooth
3) Open bluetooth.pro as a project in Qt. In my Linux OS location:
/opt/Qt5.12.3/5.12.3/Src/qtconnectivity/src/android/bluetooth
4) Choose required build for your current Android version. 
5) Build release and be happy! Now you can make pair with any Bluetooth device.
