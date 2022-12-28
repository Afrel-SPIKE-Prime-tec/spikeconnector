# spikeconnector
![spike_connector](https://user-images.githubusercontent.com/5597377/125667515-099c3969-b7d1-4cc6-96f6-db369cd490be.png)

## 概要
LEGO(R) SPIKE PrimeのHubに接続するコネクタのプリント基板（PCB）です。

コネクタの形状はWeDo2.0/Powered UP/Boostと互換性があります。

## ファイルの説明
・SPIKE_CONNECTOR.COMP：PCBのCADデータです。P板.com( https://www.p-ban.com/ )で配布している無料CAD「CADLUS X」を使って展開・編集することができます。P板.comに発注することで基板を製造可能です。カードエッジ部分は抜き差しで摩耗しますので、基板製造時にはハンダレベラー処理をお勧めします。


## 組み立て方法
![pcb_photo](https://user-images.githubusercontent.com/5597377/125736662-b56891c7-aa2d-4d15-8239-ef3be248ee64.jpg)

・上記の写真は厚さ1.2mmで製造した例です。カードエッジの反対側にプラ板を貼って、厚さを2.8mmくらいに調節します。

・センサーやモーターを取り付けたい場合、SPIKE用のfemale型コネクタを取り付けます。

・6pinのピンヘッダもしくはピンソケットを2つ取り付けます。

・ジャンパーワイヤーで接続します。

![photo2](https://user-images.githubusercontent.com/5597377/128140714-18edd984-eb81-4fa9-84d4-1d8cf7827ddf.jpg)

## 使い方の例
![2021-07-14_16-40-09_398](https://user-images.githubusercontent.com/5597377/125670871-a2a5b117-0fb5-45a1-8732-45153e1c2b46.jpg)
・延長ケーブルの自作。

・測定器をつないで、通信内容をモニタする。

・センサーを自作する。

## Pin assign 

![spike_connector_female](https://user-images.githubusercontent.com/5597377/126178875-03f07174-6b53-44fc-aa23-5410b7e76123.jpg)

1:motor1

2:motor2

3:GND

4:VCC

5:Hub to Device

6:Device to Hub
