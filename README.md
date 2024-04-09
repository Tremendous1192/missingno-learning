# missingno-learning
欠測値の可視化ライブラリmissingnoの学習リポジトリ

文章の多くはGoogle翻訳を使用しています.

## 準備
```py
import missingno as msno
%matplotlib inline
```

## 可視化方法
1. ```matrix```: ```msno.matrix(df_pandas.sample(n))```
    * 行・列ごとの欠測値を可視化する.
    * サブセットを描画すると分析しやすい(多くても1000個)
1. ```bar```: ```msno.bar(df_pandas)```
    * [```polars.DataFrame.null_count```](https://docs.pola.rs/py-polars/html/reference/dataframe/api/polars.DataFrame.null_count.html)の可視化版
1. ```dendrogram```: ```msno.dendrogram(df_pandas)```
    * 変数の関係を可視化できる


## 参考URL
* [ResidentMario/missingno: Missing data visualization module for Python.](https://github.com/ResidentMario/missingno)

