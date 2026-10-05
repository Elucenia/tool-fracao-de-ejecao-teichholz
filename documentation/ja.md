<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · ja · no clinical/professional/rights approval -->

# 駆出率（Teichholz）・短縮率

[条件・出典・許諾](https://elucenia.org/ja/tools/fracao-de-ejecao-teichholz)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 左室拡張末期径

`ddve`

cm · 範囲: 2–9

### 左室収縮末期径

`dsve`

cm · 範囲: 1–8

## 方法の版

Teichholz 1976：7 D³/(2.4+D)；EFと径による容積；ASE/EACVI 2015の文脈と幾何学的限界

## 記載された計算式

容積（Teichholz） = 7 ÷ (2.4 + D) × D³ (Dはcm，容積はmL)

駆出率 = (拡張末期容積 − 収縮末期容積) ÷ 拡張末期容積 × 100

短縮率 = (左室拡張末期径 − 左室収縮末期径) ÷ 左室拡張末期径 × 100

## 限界・対象集団

Teichholzの推定は、心室径と心室容積の幾何学的な関係に依存します。原研究では、壁運動の協調異常がない場合の一致は良好で、協調異常がある場合は不良でした。局所的な変化があり得る冠動脈疾患では注意が必要です。一つの径から算出した駆出率は、心室の形状に適した方法に代わるものではありません。

## 参考文献

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
