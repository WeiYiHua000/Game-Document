# MouseOverMessageBox : MonoBehaviour

## 描述

鼠标悬浮提示信息框控制脚本，自动控制提示框大小，换行，位置跟随鼠标

### 命名空间

GameUI

## 变量/属性

| 类型 | 名称    | 读写性（只读，读写） | 描述       |
| ---- | ------- | -------------------- | ---------- |
| Text | header  | 读写                 | 信息框标题 |
| Text | content | 读写                 | 信息框内容 |

## 公共函数

### void SetTexts(string headerText, string contentText)

设置文本框的文字，并根据字数设置换行和文本框大小

参数：

| 类型   | 名称        | 描述       |
| ------ | ----------- | ---------- |
| string | headerText  | 信息框标题 |
| string | contentText | 信息框内容 |

------
### void SetPosition()

根据鼠标在屏幕上的位置设置信息框的朝向和位置

------