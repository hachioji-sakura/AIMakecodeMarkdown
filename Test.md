### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly 1
### @hideIteration true 
### @explicitHints 1

# 6. チームに警告する

## Introduction step @unplugged

![Alert-team](/static/hour-of-code/alert.gif)

# チームに警告する

## ステップ 1

`||hourOfCode: チームに警告||`ブロックを`||hourOfCode: ハザードが発見された場合||`ブロックの中にドラッグして、チームに警告できるようにしてください。

```ghost
hourOfCode.alertTeam()
```

```template
while (hourOfCode.agentLookForHazards()) {
    if (hourOfCode.agentSeeHazard()) {
        
    }
}
```

```package
minecraft-hoc2019=github:microsoft/pxt-minecraft-hoc2019
```