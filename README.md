$ngspice filename.cir
$run

グラフを書く
$plot v(a) v(y)

詳細な値をファイルに出力
$asciiplot v(a) v(y) > hogehoge.txt

電圧源の平均消費電流
$linearize i(Vdd)
$linearize i(Vdd)
