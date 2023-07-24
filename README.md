# FF14 数据集

## 数据提取

下载 [SaintCoinach](https://github.com/xivapi/SaintCoinach/releases) 的 CMD 工具，并在工具目录通过命令行执行：

```
.\SaintCoinach.Cmd.exe C:\{{游戏路径}}\最终幻想XIV
```

开启工具后首先执行下面命令将语音设置为简体中文：


```
> lang chs
```

然后提取数据集：


```
> rawexd
```

提取得到的数据集会在 `.\{{版本号}}\rawexd` 目录下，将其移动至本项目下即可完成数据更新
