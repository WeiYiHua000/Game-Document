# SelectHorizontalScroll : MonoBehaviour

## 描述

无限水平滚动列表，根据鼠标拖动和鼠标选择控制水平滚动，并根据当前居中的选项显示详细信息

### 命名空间

GameUI

### 接口

IDragHandler, IPointerDownHandler, IPointerUpHandler

## 变量/属性

| 类型              | 名称         | 读写性（只读，读写） | 描述                       |
| ----------------- | ------------ | -------------------- | -------------------------- |
| event Action<int> | selectAction | 读写                 | 选择的事件 int指选择的编号 |


## 公共函数

### void Select(int infoIndex, RectTransform itemRectTransform)

选择选项，并调用选择事件

参数：

| 类型          | 名称              | 描述         |
| ------------- | ----------------- | ------------ |
| int           | infoIndex         | 选项的编号   |
| RectTransform | itemRectTransform | 选项的UI变换 |

------