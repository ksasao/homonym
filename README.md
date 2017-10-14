# 同音異義語の一覧
同音異義語のある名詞をまとめた辞書です。

## ダウンロード
- https://github.com/ksasao/homonym/blob/master/homonym-mecab_20171014.zip?raw=true

## 解説
MeCab 用IPA 辞書 mecab-ipadic
- http://taku910.github.io/mecab/#download

mecab-ipadic-NEologd : Neologism dictionary for MeCab
- https://github.com/neologd/mecab-ipadic-neologd/blob/master/README.ja.md
    - 2017/10/09更新
    - https://github.com/neologd/mecab-ipadic-neologd/commit/bca100e555199f913317b7958f114e77fac38e9d

を元に作成しています。

ファイルは以下の2種類があります。扱いやすいほうをご利用ください。

1. homonym.txt
```
よみ1,同音異義語1
よみ1,同音異義語2
よみ1,同音異義語3
よみ2,同音異義語4
  :
```

2. homonym2.txt
```
よみ1,同音異義語1,同音異義語2,同音異義語3
よみ2,同音異義語4,...
  :
```

## データの内容について
- 表記ゆれ、漢字変換ミスが良く利用されているケースが含まれています。
- 同音異義語として、読みと異なる複数の語句が含まれている場合があります。
例) よみ「ごちうさ」に対して同音異義語「ごちうさ」「ご注文はうさぎですか?」
- (, ), <, > など括弧記号を含むもの、顔文字は除外しています。

## License
ライセンスは、元のデータのライセンスに準拠し、Apache License, Version 2.0 です。
- https://github.com/neologd/mecab-ipadic-neologd/blob/master/COPYING
