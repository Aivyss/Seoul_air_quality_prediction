# Seoul Air Quality Prediction

# 1. テーマ

ソウルのPM10とPM2.5を予測するマシンラーニング

# 2. 企画、目標

ソウルはPM10とPM2.5で悩まされ、外出するすると必ずマスクをつけるようになりました。韓国の国内で発生したものだとしたら、四季によることは少ないことが当然ですが、冬と春はひどく濃いPM2.5で、中国を疑っています。

それで、私たちは北京とソウルの空気のデータを使い、ソウルの一年間のPM10とPM2.5の予報が出来るようにするとともにどのくらい中国からの影響があるのか試してみようとしております。

# 3. 機能

風速や風向、日付を入力し、その日のPM10とPM2.5を予報する機能

# 4. 開発の環境と流れ

## 4. 1. 環境

- 使用言語：Python
- フレームワーク：Tensorflow, Keras, Seabon, Numpy, Pandasなど
- ツール：Google Colab

## 4. 2. 流れ

1. 試料の調査
2. データの処理
3. モデリング
4. 予測
5. 評価
6. 視覚化

# 5.メンバー

- オ·ソクヒョン
- イ·ハンギョル
- チョン·ハヨン

# 6. 参考資料

## 6. 1. （韓国）ソウルのデータ

[http://www.airkorea.or.kr/web/realSearch?pMENU_NO=97](http://www.airkorea.or.kr/web/realSearch?pMENU_NO=97)

[https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36](https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36)

## 6. 2. （中国）北京のデータ

[https://www.kaggle.com/joshuapaulbarnard/beijing-air-quality-pm25-from-2010-to-2017](https://www.kaggle.com/joshuapaulbarnard/beijing-air-quality-pm25-from-2010-to-2017)
