### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 2 – Paterns, paterns, paterns...

## ステップ 1
異なる毛皮のパターンを持ついくつかのオセロットから、大量の写真データを収集したので、データセットをコーディングできます。

## ステップ 2
`||Datasets: make dataset||` コーディングブロックを使用して、`||Datasets: historical||` に設定します。その中に、収集したすべての `||Input: trap camera data||` を配置します。

## ステップ 3
最後のステップとして、写真データからオセロットの毛皮のパターンを抽出する必要があります。`||Datasets: extract patterns||` コーディングブロックを使用してください。
コードを実行すると、オセロットのパターンのプレビューがコンパイルされます。

```ghost
Input.trap1_PR()
Input.trap2_PR()
Input.trap3_PR()
Datasets.extractPatterns_PR()
Datasets.setOfData_PR(datasetType.historical, function() {})
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```