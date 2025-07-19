### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 2 – この世のものではない

## ステップ 1
すべての衛星ビーコンを設置したので、衛星を**制御**し、送り返される情報から**現在の**データセットをコーディングする必要があります。

## ステップ 2 
まず、`||loops: 最初だけ||`コーディングブロックの中に`||Input: 衛星を制御||`コーディングブロックを使用してください。その中に`||Datasets: データセットを作成||`コーディングブロックを配置し、そのブロックを`||Datasets: 現在の||`データセットに設定してください。

## ステップ 2 
その後、すべての`||Input: 位置の衛星データ||`を中に配置してください。実行すると、衛星カメラが現在のデータセットのデータを収集しながら村の上空をパンしているのを確認できます。

```ghost
Input.beacon1_SF()
Input.beacon2_SF()
Input.beacon3_SF()
Input.beacon4_SF()
Input.beacon5_SF()
Input.runSatelite_SF(function() {})
Datasets.setOfData_SF(datasetType.historical, function() {})
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```