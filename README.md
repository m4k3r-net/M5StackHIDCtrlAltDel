# About 概要
let M5Stack to send keys(ctrl+alt+del) to PC/smart phones like BT keyboard via BLE HID. Especially CTRL+ALT+DEL keys :-)\
M5StackがBLE HIDデバイスつまりBTキーボードになり、PCやスマホにキーを送信できます。特にCTRL+ALT+DEL。

<img src="https://user-images.githubusercontent.com/618417/38174769-6b217e7c-360d-11e8-9a94-2b2ac8410b8e.jpg" width="400px">

# Build ビルド
Follow instructions on the below link to setup Arduino for M5Stack. \
以下のリンクに従ってM5StackをArduino向けにセットアップしてください。

https://github.com/m5stack/M5Stack

Clone this project and compile M5StackHIDCtrlAltDel.ino and upload to M5Stack. \
このプロジェクトをCloneして、M5StackHIDCtrlAltDel.ino をコンパイルし、M5Stackにアップロードしてください。

# Usage 使用方法
It works like BT Keyboard. You can send key code below when you push buttons of M5Stack. \
Bluetoothキーボードのように動作します。ボタンを押すと以下のキーコードを送信します。

* A button: Hello from M5Stack!
* B button: CTRL+ALT+DEL :-)

# Restriction 制限事項
Currently, it does not work after reset M5Stack. Please remove BLE device from PC/SmartPhone and add device again. \
M5StackをリセットするとBLEがうまく動作しないようです。その場合、PC/スマホ側でBTデバイスを削除してから、追加しなおしてください。

Resolution of this problem is welcome !!! \
解決方法募集中！！！
