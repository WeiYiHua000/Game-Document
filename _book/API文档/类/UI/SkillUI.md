# SkillUI : MonoBehaviour

## 描述

控制游戏内的玩家技能释放

### 命名空间

GameUI

## 公共函数

### SkillButton CreateSkillButton(string name, Sprite sprite, string description, float CD, Action skillAction)

根据参数创建技能按钮

返回值：

| 类型        | 描述                 |
| ----------- | -------------------- |
| SkillButton | 创建的技能按钮的脚本 |

参数：

| 类型   | 名称        | 描述         |
| ------ | ----------- | ------------ |
| string | name        | 技能名称     |
| Sprite | sprite      | 技能图片     |
| string | description | 技能描述     |
| float  | CD          | 技能冷却时间 |
| Action | skillAction | 技能执行事件 |

------

### void DisableSkillButton(string name)

禁用指定技能名称的技能按钮

参数：

| 类型   | 名称 | 描述                                 |
| ------ | ---- | ------------------------------------ |
| string | name | 要禁用的技能的名称（同名禁用最早的） |

------

### void EnableSkillButton(string name)

启用指定技能名称的技能按钮

参数：

| 类型   | 名称 | 描述                                 |
| ------ | ---- | ------------------------------------ |
| string | name | 要启用的技能的名称（同名启用最早的） |

------

### void DestroySkillButton(string name)

删除指定技能名称的技能按钮

参数：

| 类型   | 名称 | 描述                                 |
| ------ | ---- | ------------------------------------ |
| string | name | 要删除的技能的名称（同名删除最早的） |

------

