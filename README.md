raspberrypi-tempbot
===================

Raspberry Pi+SC162C+USBRHを使った温湿度計
https://pbs.twimg.com/media/BsvvqbaCEAA5xcS.jpg

Raspberry PiとSC162C(aitendoで購入した16x2 LCDモジュール)を使って温度と湿度を表示します。
温度と湿度はStrawberry LinuxのUSBRHが借りられたのでそれを使っていますが、なんでもOKだと思います。
最終的には不快指数も計算してtwitterでつぶやいています。
https://twitter.com/iwalab_tempbot

Raspberry PiでUSBRHを使うためにUSBRH on Linux(http://www.dd.iij4u.or.jp/~briareos/soft/usbrh.html)を使わせていただきました。

Twitter投稿を実現するためにPython+OAuthを使っていますが、
http://qiita.com/yubais/items/dd143fe608ccad8e9f85　を参考にさせていただきました。
