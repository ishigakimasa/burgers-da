# ファイルの説明
Burgers-rect.ipynbが真値となるデータの生成プログラム
Burgers-ETKF.ipynbがデータ同化のプログラム
makeObs.ipynbが（疑似）観測データの生成プログラム
plot.ipynbがデータ同化の結果のプロット用のプログラム

# 準備
- 各プログラムはJuliaで書いてあるので，Juliaのインストールする
- PythonのJupyter labもしくはJupyter notebookをインストールする
- JuliaでIJuliaをインストール。他にも必要なライブラリをインストール

## 計算のための準備
data_true, data_obs, data_resultというディレクトリを作成しておく。

# 計算の実行
1. Burgers-rect.ipynbを実行
2. makeObs.ipynbを実行
3. Burgers-ETKF.ipynbを実行
4. plot.ipynbを実行

