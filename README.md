# test1
ロボットシステム学



課題1


内容：

raspberrypi2を使用し、GPIO25ピンから信号を出力してLEDを点滅させました。

$ echo 1 > /sys/class/gpio/gpio25/value

で点灯

$ echo 0 > /sys/class/gpio/gpio25/value

で消灯

回路構成：

・raspberrypi2

・赤色LED

・100Ωの抵抗




Reference

以下のサイトを参考にしました。

http://independence-sys.net/main/?p=2181

http://blog.asial.co.jp/894

https://www.megaleecher.net/Raspberry_Pi_2_Schematic_And_Pinout_Diagram
