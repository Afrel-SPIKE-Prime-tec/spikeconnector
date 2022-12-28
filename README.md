# spikeconnector
![photo2](https://user-images.githubusercontent.com/5597377/128140714-18edd984-eb81-4fa9-84d4-1d8cf7827ddf.jpg)

## 概要
LEGO(R) SPIKE PrimeのHubに接続するコネクタのプリント基板（PCB）です。

コネクタの形状はWeDo2.0/Powered UP/Boostと互換性があります。

## ファイルの説明

![spikeconnector_pcb](https://user-images.githubusercontent.com/5597377/209868411-05b381cb-5f69-431f-bc59-2bb1a22dadd1.png)

・SPIKE_CONNECTOR.COMP：基板のCADデータです。P板.com( https://www.p-ban.com/ )で配布している無料CAD「CADLUS X」を使って展開・編集することができます。P板.comに発注することで基板を製造可能です。カードエッジ部分は抜き差しで摩耗しますので、基板製造時にはハンダレベラー処理をお勧めします。

![Clipboard01](https://user-images.githubusercontent.com/5597377/209770294-736164fd-c69b-4233-a1c8-2cc52d024490.png)

・spike_connector_cover.stl：厚みを調節するプラ板の3Dプリンタ用データです。厚さ1mmの基板と組み合わせることを想定しています。

## 組み立て方法
![pcb_photo](https://user-images.githubusercontent.com/5597377/125736662-b56891c7-aa2d-4d15-8239-ef3be248ee64.jpg)

・基板の裏側にプラ板を貼って、全体の厚さを2.8mmくらいに調節します。

・センサーやモーターを取り付けたい場合、SPIKE用のfemale型コネクタを取り付けます。

・6pinのピンヘッダもしくはピンソケットを2つ取り付けます。

・ジャンパーワイヤーで接続します。

![connector_mod](https://user-images.githubusercontent.com/5597377/209772079-ff59a2d7-ded7-4bf3-9a90-358d74ae1816.jpg)

3Dプリンタで出力したプラ板と基板を組み合わせた例です。

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
