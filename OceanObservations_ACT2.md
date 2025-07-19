### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 2 – 水中データ

## ステップ 1
センサーが設置されたので、**4つ**のセンサーからのデータをすべて保持する**1つ**のライブデータセットを作成する必要があります。
これが完了すると、4つのモニターで水面下で何が起こっているかを確認し、マッピングできるようになります。

## ステップ 2 
まず、`||loops: 最初だけ||`コーディングブロックの中に`||Datasets: データセットを作成||`コーディングブロックを使用してください。
そのブロックを`||Datasets: リアルタイムデータ||`データセットに設定してください。

## ステップ 3
その後、データセット内に`||Input: センサーのデータ||`を配置してください。

```ghost
Input.sensor1_OO()
Input.sensor2_OO()
Input.sensor3_OO()
Input.sensor4_OO()
Datasets.setOfData_OO(datasetType.historical, function() {})
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```
