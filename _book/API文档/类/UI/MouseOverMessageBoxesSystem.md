# MouseOverMessageBoxesSystem : MonoBehaviour

## 描述

鼠标悬浮提示信息框系统，含有简易的对象池

### 命名空间

GameUI

## 变量/属性

| 类型  | 名称     | 读写性（只读，读写） | 描述                 |
| ----- | -------- | -------------------- | -------------------- |
| float | waitTime | 读写                 | 唤出信息框的等待时间 |


## 公共函数

### MouseOverMessageBox ShowMessageBox(string header, string content)

显示一个信息框，从对象池里拿

返回值：

| 类型                | 描述         |
| ------------------- | ------------ |
| MouseOverMessageBox | 显示的信息框 |

参数：

| 类型   | 名称    | 描述 |
| ------ | ------- | ---- |
| string | header  | 标题 |
| string | content | 内容 |

------
### void HideMessageBox(MouseOverMessageBox messageBox)

隐藏指定的信息框，放回对象池

参数：

| 类型                | 名称       | 描述           |
| ------------------- | ---------- | -------------- |
| MouseOverMessageBox | messageBox | 要隐藏的信息框 |

------
