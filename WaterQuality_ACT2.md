### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 2 – 蛇口から直接

## ステップ 1
周囲の川から水のサンプルを収集したので、各場所からの水のデータで**現在の**データセットをコーディングしてください。

## ステップ 2 
まず、`||Datasets: 現在の||`に設定された`||Datasets: データセットを作成||`コーディングブロックを使用してください。その中に、各場所からのすべての`||Input: 水データ||`を配置してください。

```ghost
Input.waterData1_WQ()
Input.waterData2_WQ()
Input.waterData3_WQ()
Datasets.setOfData_WQ(datasetType.historical, function() {})
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```