### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 3 – ここにも汚染物質、そこにも汚染物質

## ステップ 1
汚染源を見つけるAIをコーディングする必要があります。これを行うために、前のアクティビティでコーディングした**現在の**データセットを**解析**し、汚染物質の濃度が最も高い場所を見つける必要があります。

## ステップ 2
まず、`||AI: 教師あり機械学習||`コーディングブロックを使用し、その中に**現在の**に設定された`||Datasets: データセット入力||`コーディングブロックを配置してください。

## ステップ 3
その後、`||AI: 水データを解析||`コーディングブロックを配置してください。続いて、`||Output: 汚染源を特定||`コーディングブロックを配置してください。
コードを実行すると、AIが汚染の発生源となっている場所を見つけます。

```ghost
Datasets.input_WQ()
AI.ml_WQ(function(){})
AI.analyze_WQ()
Output.locatePollution_WQ()
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```