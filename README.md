# Display-count-html
ロボットシステム学の課題として授業の内容で製作したものです。 
  
## 概要
htmlでwebページを設定し、そこにROS内で動かしているカウントするプログラムの値を、web上で確認することができます。

## 動作動画
以下のリンク先に、動作動画を載せてあります。  
[動作動画](https://youtu.be/BT9JyNWANd0)

## 必要なもの
* ROSを動かすことができる環境
* Webページを表示できる環境

## 実行方法
まず、実行させる環境でROSを動かせるようにします。  
以下のコマンドでgit cloneします。  
`git clone https://github.com/Shimataku9311/Display-count-html.git`

次にifconfigを使用して、inetのアドレスを確認しておきます。  

以下のコマンドを入力することで、プログラムを動作させます。
停止コマンドはCtrl + Cとなっています。
`roslaunch Display-count-html mypkg.launch`  

webページを立ち上げて、アドレス欄に[http://(確認したinetアドレス):8000]と打ち込みます。  
プログラムを動かしていない間は、ネットワークに接続できていないという状態に入っています。

カウントが始まっていない間は「not receive」と表示されます。  
カウントが始まると「date:~」と数字が表示されます。


## ライセンス
GPLv3ライセンスの下でライセンスされています。[ライセンス]( Display-count-html/LICENSE )

## 参考サイト
[RaspberryPi3用UbuntuMATEのイメージ書き込み方](https://memoteki.net/archives/1308)
