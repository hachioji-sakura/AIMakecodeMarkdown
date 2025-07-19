### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 3 – Professional Tracker.

## ステップ 1
オセロットを追跡するAIをコーディングする必要があります。 
サバンナから入ってくる**現在の**データを使用し、 
前のアクティビティで作成した**過去**データセットと**比較**します。

## ステップ 2
まず、`||AI: 半教師あり機械学習||` コーディングブロックを使用し、その中に `||Datasets: データセット入力||` コーディングブロックを配置します。
その後、`||Datasets: データセットを比較||` コーディングブロックを配置します。**現在の**データセットと**過去**データセットに設定します。

## ステップ 3
次に、`||AI: パターンデータを解析||` コーディングブロックを配置します。続いて、`||Output: オセロットを発見||` コーディングブロックを配置します。 
これでコードを実行すると、オセロットの位置の地図が表示されます。



```ghost
Datasets.compare_PR()
Datasets.input_PR()
AI.ml_PR(function(){})
AI.analyze_PR()
Output.locateOcelots_PR()
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```