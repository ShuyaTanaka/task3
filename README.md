# task3 概要  
課題1で実現できなかったLEDの点滅を,今回はインターネットで調べたものをもとにpythonを使用して行う。  
  
# 動作環境  
Ubuntu 18.04  
rasberry pi 4 model B  
  
# 実験で使用したもの  
LED(黄) × 2  
抵抗 (300Ω) × 2  
ジャンパー線 × 4  
T型プリント基板  
ピンリボンケーブル  
ブレッドボード  
  
# 実行順  
`vi led.py` に書かれたコードに対し、  
  
`sudo python3 led.py` で実行可能となる。  

# 実験内容詳細  
実行後、GPIO23とつながっているLEDが0.15秒点灯、0.15秒消灯という処理を20回繰り返す。  
                       ↓  
その処理が終わるのと同時に、今度はGPIO16とつながっているLEDが0.05秒点灯、0.05秒消灯という処理を50回繰り返す。  
                       ↓  
                      終了  

# デモ動画  


# 参考文献  


# ライセンス  
>[GNU General Public License v3.0](https://github.com/ShuyaTanaka/task3/blob/main/COPYING)
