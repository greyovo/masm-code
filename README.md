# masm-code README

这学期我们学校在上8086汇编课程，使用Masm for Windows写汇编程序。而Masm fow Windows这个软件，UI丑，部分功能还收费。于是我写了这个扩展。**PS:我写的有点急，可能有一点小bug。以及：Mocha我在学了，下次一定写测试。**

## Features（谁教教我这个词怎么翻译合适）

+ Intel 8086汇编的语法高亮
+ 自动下载Masm和DOSBox。无需手动配置。

## Requirements（还有这个词）

无！有手就能用！

## 设置

目前可以在`settings.json`中设置DOSBox的窗口大小,默认为1024*768。你也可以自行修改为你觉得爽的大小。
```json
    {
        "masm-code.DOSBox.BoxWidth":1024,
        "masm-code.DOSBox.BoxHeight":768
    }
```

## 已知存在的bug

+ 有的时候，如果你缺少了masm或者dosbox的文件，他会显示正在下载，然后不动了。怎么办呢。打开目录`C:/Users/你的名字/AppData/Roaming/Code/User/globalStorage/kaixa.masm-code/`把里面大小为0kb的删掉，然后重启vscode。（我还没学会怎么重新加载扩展qaq）
+ 其他bug，遇到的我都解决了，但是我感觉可能还是会遇到奇奇怪怪的问题。这时候你可以在[这里](https://github.com/Woodykaixa/masm-code/issues)反馈