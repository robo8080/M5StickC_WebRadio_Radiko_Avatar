# M5StickC_WebRadio_Radiko_Avatar
M5StickC Plus用アバター表示、レベルメーター付きRadikoプレイヤー

![画像1](images/image1.png)<br><br>


wakwak-kobaさんの M5Stack Radikoプレイヤーをアバターとレベルメーターを同時に表示できるように改造。<br>
さらにM5StickC Plusで動くようにしました。<br>

Radikoプレイヤーは、wakwak-kobaさんのWebRadio_Japanをベースにさせていただきました。<br>
オリジナルはこちら。<br>
WebRadio_Japan <https://github.com/wakwak-koba/WebRadio_Japan><br>


Avatar表示は、meganetaaanさんのm5stack-avatarをベースにさせていただきました。<br>
オリジナルはこちら。<br>
An M5Stack library for rendering avatar faces <https://github.com/meganetaaan/m5stack-avator><br>

---
### このプログラムを動かすのに必要な物 ###
* M5StickC Plus
* [スピーカーHat](https://www.switch-science.com/catalog/5754/ "Title")
* VSCode
* PlatformIO<br>

使用しているライブラリ等は"platformio.ini"を参照してください。<br>

---
### WiFiの設定 ###
* "M5StickC_WebRadio_Radiko_Avatar.ino"の1行目付近、SSIDとPASSWORDを設定してください。
* SSIDとPASSWORDを設定せずにSmartConfigを使用することもできます。
その場合はiOSかAndroidの「Espressif Esptouch」アプリから設定します。

---
ビルド済みファームウェアをM5Burner v3に公開しました。すぐに使ってみたい方はこちらをどうぞ。<br>

![画像2](images/image2.png)<br><br><br>

### 使い方 ###
* M5StickC PlusとスピーカーHatが必要です。<br>
* Wi-Fiの設定はSmartConfigを使用、iOSかAndroidの「Espressif Esptouch」アプリから設定します。<br>
* ボタンA：選曲 ボタンA長押し：音量＋ ボタンB：音量<br><br>


