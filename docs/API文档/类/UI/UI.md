# UI

所有关于UI模块的类

| 类名：基类                                                   | 描述/功能                                                    |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [UIManager : MonoBehaviour](UIManager.md)                    | 单例模式，在此保存了其他UI脚本的引用，游戏内使用UI从这里调用 |
| [SkillUI : MonoBehaviour](SkillUI.md)                        | 控制游戏内的玩家技能释放                                     |
| [SkillButton : MonoBehaviour](SkillButton.md)                | 由SkillUI控制，根据cd弹出技能释放按钮，cd读条等              |
| [MouseOverMessageBoxesSystem : MonoBehaviour](MouseOverMessageBoxesSystem.md) | 鼠标悬浮提示信息框系统，简易的对象池                         |
| [MouseOverMessageBoxTrigger : MonoBehaviour](MouseOverMessageBoxTrigger.md) | 鼠标悬浮提示信息框触发器，将此脚本挂在需要提示框的UI物体上，设置内容文本后UI物体可以唤出信息框 |
| [MouseOverMessageBox : MonoBehaviour](MouseOverMessageBox.md) | 鼠标悬浮提示信息框控制脚本，自动控制提示框大小，换行，位置跟随鼠标 |
| [MessageTips : MonoBehaviour](MessageTips.md)                | 在游戏右下角生成信息提示，可以用在事件提示，单位死亡提示等等，还支持倒计时 |
| [MessageTipObject : MonoBehaviour](MessageTipObject.md)      | 由MessageTips控制，控制信息和倒计时                          |
| [MiniMap : MonoBehaviour](MiniMap.md)                        | 游戏小地图，目前是使用额外的摄像机，可以控制大小宽度透明度   |
| [MainMenu : MonoBehaviour](MainMenu.md)                      | 主菜单UI，控制UI界面动画，打开网页链接，退出游戏             |
| [SoliderInfoUI : MonoBehaviour](SoliderInfoUI.md)            | 根据鼠标射线获取点击的士兵，并根据士兵阵营调用显示士兵信息的脚本 |
| [EnemyInfo : MonoBehaviour](EnemyInfo.md)                    | 显示敌方士兵信息并跟随士兵移动，显示攻击和防御               |
| [SelectHorizontalScroll : MonoBehaviour](SelectHorizontalScroll.md) | 无限水平滚动列表，根据鼠标拖动和鼠标选择控制水平滚动，并根据当前居中的选项显示详细信息 |
| [SelectHorizontalScrollItem : MonoBehaviour](SelectHorizontalScrollItem.md) | 无限水平滚动列表选项，由SelectHorizontalScroll控制，获取鼠标点击 |