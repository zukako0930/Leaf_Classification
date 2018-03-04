# Leaf_Classification
KaggleコンペLeaf Classificationをやってみる。

# 特徴量
99個のクラスに対して各クラス16枚の画像+3つの特徴量<br>
16枚は少なすぎるな、、、

# 手法
CNN + ???<br>
???に決定木を用いれば、大まかな分類をした後でCNNにかけることができる?<br>
RandomForest -> CNN -> 出力
# 方針
おそらくデータ拡張の仕方が大事。<br>
trainとtestを分けてからデータ拡張を行うように注意。

# その他
