# wc3 中式人魔大战

## 文件放哪里

| 版本 | 路径 |
|---|---|
| Reforged | `<安装目录>\_retail_\Units\` |
| 经典版 1.29（启动器安装） | `<安装目录>\Units\zhCN\` |

两个文件：

- `HumanUnitStrings.txt` —— 英雄 / 兵种 / 建筑
- `HumanAbilityStrings.txt` —— 英雄技能

## 什么编码

**UTF-8，无 BOM，换行用 CRLF。**

存成 GBK 会乱码甚至崩溃；加了 BOM 会让第一个 `[ID]` 段失效。

## 怎么还原

把这两个文件删掉，游戏立刻恢复原名。
