# MessageTips : MonoBehaviour

## 描述

游戏右下角弹出的消息信息提示

### 命名空间

GameUI

## 公共函数

### void CreateMessageTip(string title, Sprite sprite, string details = null, float countdownTime = 0)

创建一条信息提示

参数：

| 类型   | 名称          | 描述           |
| ------ | ------------- | -------------- |
| string | title         | 消息的标题     |
| Sprite | sprite        | 消息的图片     |
| string | details       | 消息的详细信息 |
| float  | countdownTime | 消息的倒计时   |

------
### void RemoveTip(MessageTipObject tipObject)

移除消息提示

参数：

| 类型             | 名称      | 描述             |
| ---------------- | --------- | ---------------- |
| MessageTipObject | tipObject | 要移除的消息提示 |

------