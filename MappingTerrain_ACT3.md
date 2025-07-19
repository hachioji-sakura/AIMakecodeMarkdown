### @explicitHints true
### @flyoutOnly 0

# Activity 3 – 異常を検出する

## ステップ 1
このアクティビティでは、作成したデータセットを機械学習アルゴリズムの中で使用する必要があります。このアルゴリズムはデータセット内の異常を検索し、地図上でそれらを特定する必要があります。まず、`||loops: 最初だけ||`コーディングブロックの中に`||AI: 機械学習||`コーディングブロックを使用してください。

## ステップ 2
その中に、`||Datasets: データセット入力||`コーディングブロックを配置してください。その後、`||AI: データを解析||`コーディングブロックを配置してください。

## ステップ 3
データをインポートして解析したので、アルゴリズムには結果があるはずです。しかし、地図上で結果を確認できるように、`||Output: 位置を表示||`コーディングブロックを配置してください。

```ghost
Datasets.input_MT()
AI.analyze_MT()
Output.showLocations_MT()
AI.ml_MT(function() {})
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```