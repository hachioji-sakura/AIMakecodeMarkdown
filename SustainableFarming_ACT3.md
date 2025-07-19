### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 3 – 予測分析

## ステップ 1
最適な植栽場所を見つけるAIをコーディングする必要があります。
前のアクティビティでコンパイルした**現在の**データセットを使用し、
衛星ステーションがすでに持っている**過去の**データセットと**比較**する必要があります。

## ステップ 2
まず、`||AI: 半教師あり機械学習||`コーディングブロックを使用し、その中に`||Datasets: データセット入力||`コーディングブロックを配置してください。
その後、`||Datasets: データセットを比較||`コーディングブロックを配置してください。**現在の**データセットと**過去の**データセットに設定してください。

## ステップ 3
その後、`||AI: 予測分析を実行||`コーディングブロックを配置し、続いて`||Output: 最適な農地を発見||`コーディングブロックを配置してください。
コードを実行すると、AIが最適な農地を発見し、それらを照らし出します。

```ghost
Datasets.compare_SF()
Datasets.input_SF()
AI.ml_SF(function(){})
AI.analyze_SF()
Output.locateFarm_SF()
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```