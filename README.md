# BinaryToHexTextBlock-UIFlow
M5Stack社のUIFlowでByte型(0-255の数値)のリストを16進テキストに変換するブロックです。
ブロック内部の処理で、[binascii](https://docs.python.org/ja/3/library/binascii.html)を利用して変換をかけています。

## 使い方
byteListにByte型のリスト、textVariableに処理結果を格納するテキスト用変数を入れて使います。

![image](screenshot.png)

