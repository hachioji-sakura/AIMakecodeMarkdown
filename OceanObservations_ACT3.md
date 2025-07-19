### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

```template
//
```

### @explicitHints true
### @flyoutOnly 0

# Activity 3 – 未来の備え

## ステップ 1
安定したデータストリームが入ってくるようになったので、これらのサンゴ礁に対する気候変動の影響に関する研究を開始することができます。しかし、センサーが故障した場合に備えて、AIを使用してセンサーに到達し、自動的に修理することを求めています。
これは、私たちが収集している**リアルタイムデータ**を使用した**自律ナビゲーション**によって可能です。

## ステップ 2 
`||loops: 最初だけ||`コーディングブロックの中に`||AI: 機械学習||`コーディングブロックを使用してください。
このブロック内に、`||datasets: リアルタイムデータセット||`に設定された`||Datasets: データセット入力||`コーディングブロックを配置してください。
その後、`||AI: 地形データを解析||`コーディングブロックを配置してください。

## ステップ 3
その後、`||AI: ルートを生成||`コーディングブロックを配置してください。
実行すると、AIはエージェントが進むルートを生成し、さまざまなサンゴと衝突しないようにします。
また、海底の地形を地図上で確認することもできます。

```ghost
AI.analyze_OO()
AI.ml_OO(function() {})
Datasets.input_OO()
AI.genRoutes_OO()
```

```package
aicustomblocks=github:hachioji-sakura/AICustomBlocks
```