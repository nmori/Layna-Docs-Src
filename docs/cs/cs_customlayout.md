## 攻略チートシートについて

* このチートシートはテーマを絞ってガイドする「攻略本」的なものです。

## やりたいこと

* 表示する文字をかっこよくします

## 謝辞

* [蓬莱軒](https://twitter.com/HoraiChan)さんのテンプレートを題材として活用させていただいております

* テンプレートは[こちら](https://twitter.com/HoraiChan/status/1704830149479547055?s=20)から入手できます。

## 設定

1. テンプレートは[こちら](https://twitter.com/HoraiChan/status/1704830149479547055?s=20)から入手し、ファイルをすきなフォルダに展開します。

2. OBSに自分が使いたいレイアウトのhtmlファイルを貼りつけます。
![Image title](../images/cs_customLayout_p01.png)

3. れいなのアクション画面でソース名を選びます。
![Image title](../images/cs_customLayout_p02.png)

4. スタイルシートを読み込みます。
![Image title](../images/cs_customLayout_p03.png)

5. 文を入れるところにタグをいれます。

* タグはリストから選んでいれます。例ではコメントテスターの最終文になっていますが、配信の文を取り込むためには、別のタグを使います（例：{#.last.comment}）

![Image title](../images/cs_customLayout_p04.png)

6. 更新条件を設定します

* コメントがくるたびにだすなら、'{comment.count}>0'と入れます。

![Image title](../images/cs_customLayout_p05.png)

これで、コメントが来るたびに表示がきれいにでます。

![Image title](../images/cs_customLayout_p06.png)
