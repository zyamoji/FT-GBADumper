# FT-GBADumper
GBA ROM Dumper using FT232HL

## なにこれ
+ FT232H, MCP23S17を使ったGBAダンパー
+ 転送速度約485kb/s
+ [同じ回路でGBも吸い出せる](https://github.com/RGBA-CRT/FT-GBDumper)
+ セーブデータの吸出しには未対応
+ セーブ消えても知りません

## About this
+ GBA Dumper using FT232HL, MCP23S17
+ Read Speed is about 485 KB/s
+ It supports GB in the same circuit.
+ It not supported save read/write.

## 回路 / Circuit
+ see [FT-GBDumper](https://github.com/RGBA-CRT/FT-GBDumper)
+ ↑の回路に5V/3.3Vスイッチを付けてください。GBAは3.3Vです。
+ Add 5V/3.3V select switch.

## その他 / other
+ その他はすべて[FT-GBDumper](https://github.com/RGBA-CRT/FT-GBDumper)と同じなので省略します。
+ All others are the same as [FT-GBDumper](https://github.com/RGBA-CRT/FT-GBDumper).

## 参考 / technical reference
+ https://github.com/sanni/cartreader
+ https://problemkaputt.de/gbatek.htm
+ Thank you.

## SS
![ScreeenShot](https://raw.githubusercontent.com/RGBA-CRT/FT-GBADumper/master/SS.png)

---
Programmed by RGBA_CRT 2018  
Project url: https://github.com/RGBA-CRT/FT-GBADumper
