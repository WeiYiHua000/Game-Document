# SelectHorizontalScrollItem : MonoBehaviour

## 描述

无限水平滚动列表选项，由SelectHorizontalScroll控制，获取鼠标点击

### 命名空间

GameUI

### 接口

IPointerClickHandler

## 变量/属性

| 类型          | 名称          | 读写性（只读，读写） | 描述       |
| ------------- | ------------- | -------------------- | ---------- |
| int           | infoIndex     | 读写                 | 选项编号   |
| string        | description   | 读写                 | 选项描述   |
| RectTransform | rectTransform | 读写                 | 选项UI变换 |

## 公共函数

### void SetInfo(Sprite sprite, string name, string description, int infoIndex, SelectHorizontalScroll selectHorizontalScroll)

设置选项的信息

参数：

| 类型                   | 名称                   | 描述             |
| ---------------------- | ---------------------- | ---------------- |
| Sprite                 | sprite                 | 选项图片         |
| string                 | name                   | 选项名称         |
| string                 | description            | 选项描述         |
| int                    | infoIndex              | 选项编号         |
| SelectHorizontalScroll | selectHorizontalScroll | 控制此选项的脚本 |

------
### void SetAlpha(float alpha)

设置选项的透明度

参数：

| 类型  | 名称  | 描述          |
| ----- | ----- | ------------- |
| float | alpha | 透明度（0-1） |

------