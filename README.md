# flutter_ble


## import flutter_blue

## Android_ManifestおよびInfo.plistの設定が必要
### Android_Manifest変更点
    <uses-permission android:name="android.permission.BLUETOOTH" />
    <uses-permission android:name="android.permission.BLUETOOTH_ADMIN" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>

###

## Android端末で実装する上では，android/app/build.gradle minSDK 19にする

## BLEを理解するには GATTについて学ぶべきである(http://yegang.hatenablog.com/entry/2014/08/09/195246)

