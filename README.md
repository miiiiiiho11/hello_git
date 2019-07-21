# どんな処理を実装したのか
初めに、パソコンのインカメラで動画を撮影し、"output.avi"という名前で保存した.次に、動画のプロパティを取得した.さらに、動画を１フレーム毎に画像に変換し、連番で名前を付けて保存した.最後に、それぞれの画像の輝度値の平均値を計算し、折れ線グラフにプロットした.

# 依存ライブラリとバージョン
openCV(4.1.0),numpy(1.16.2),matplotlib(3.0.3)

# 参考文献
OpenCV "動画を扱う"
http://labs.eecs.tottori-u.ac.jp/sd/Member/oyamada/OpenCV/html/py_tutorials/py_gui/py_video_display/py_video_display.html
'動画を保存する'のコード

Hatena Blog "Python, OpenCVを用いて動画を画像へ変換する（動画から画像の切り出し）" あさの畑
https://www.asanohatake.com/entry/2018/11/20/073000
'動画のプロパティを取得する'、'動画から画像への変換（フレームごと）'のコード

Hatena Blog "【Python】matplotlib でグラフ描画（折れ線グラフ編）" とある科学の備忘録
https://shizenkarasuzon.hatenablog.com/entry/2018/11/16/205129
matplotlibのインストールの仕方、グラフの描き方のコード

# 実行の様子
動画撮影:
![picture1](https://user-images.githubusercontent.com/53108106/61595997-cda80f00-ac38-11e9-894d-029bb284e45a.png)

グラフ:
![picture2](https://user-images.githubusercontent.com/53108106/61595998-cda80f00-ac38-11e9-9872-1dcfbc7af565.png)

