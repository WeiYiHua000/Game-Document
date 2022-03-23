# UIManager : MonoBehaviour

## 描述

单例模式，在此保存了其他UI脚本的引用，游戏内使用UI从这里调用

### 命名空间

GameUI

## 字段/属性/事件

| 类型                        | 名称                        | 读写性（只读，读写） | 描述               |
| --------------------------- | --------------------------- | -------------------- | ------------------ |
| MessageTips                 | messageTips                 | 读写                 | 游戏信息提示脚本   |
| MouseOverMessageBoxesSystem | mouseOverMessageBoxesSystem | 读写                 | 鼠标悬浮提示框脚本 |
| MiniMap                     | miniMap                     | 读写                 | 小地图脚本         |
| SkillUI                     | skillUI                     | 读写                 | 技能UI脚本         |
| SoliderInfoUI               | soliderInfoUI               | 读写                 | 显示士兵信息脚本   |

## 静态字段/属性/事件

| 类型      | 名称     | 读写性（只读，读写） | 描述         |
| --------- | -------- | -------------------- | ------------ |
| UIManager | instance | 读写                 | 单例模式引用 |
