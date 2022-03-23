# SkillButton : MonoBehaviour

## 描述

由SkillUI控制，根据cd弹出技能释放按钮，cd读条等

### 命名空间

GameUI

### 接口

IPointerClickHandler, IPointerEnterHandler, IPointerExitHandler

## 变量/属性

| 类型   | 名称      | 读写性（只读，读写） | 描述     |
| ------ | --------- | -------------------- | -------- |
| string | skillName | 读写                 | 技能名称 |


## 公共函数

### void SetInfo(string name, Sprite sprite, string description, float CD, Action skillAction)

设置技能信息

参数：

| 类型   | 名称        | 描述         |
| ------ | ----------- | ------------ |
| string | name        | 技能名称     |
| Sprite | sprite      | 技能图片     |
| string | description | 技能描述     |
| float  | CD          | 技能冷却时间 |
| Action | skillAction | 技能执行事件 |

------

### void EnableButton()

启用此按钮

------
### void DisableButton()

禁用此按钮

------
### void DestroyButton()

删除此按钮

------