# GroveLevelShifter

<img src="https://github.com/akita11/GroveLevelShifter/blob/main/GroveLevelShifter.jpg" width="320px">


<img src="https://github.com/akita11/GroveLevelShifter/blob/main/GroveLevelShifter_back.jpg" width="320px">

2本のGroveケーブルを接続して延長し、その中の電源電圧(+5V)を3.3Vに変換します。M5StackシリーズのGrove互換コネクタ（HY4pコネクタ）は電源電圧が5Vですが、信号電圧は3.3Vのため、信号電圧レベルをあわせるのに利用できます。その他のGNDと2本の信号線はそのまま接続されています。

## 使い方

2つのGroveコネクタのうち、"5V"と書いてある側（"GroveLevelShifetr"の文字がある側）に、電源供給側（M5Stackなど）からのGroveケーブルを接続します。反対側の"3.3V"と書いてある側（IC等の部品が乗っている側）のGroveコネクタの電源には3.3Vが出力されますので、Groveケーブルで3.3Vを供給したいセンサ等に接続します。


## Author

Junichi Akita (akita@ifdl.jp, @akita11)
