### **坦克大战概述**
#### *1）创建工程添加场景*
##### 创建新的工程后添加素材，找到场景后添加至Hierarchy视图。
#### *2）坦克*
##### 添加坦克至Hierarchy视图，为坦克添加刚体，编写代码控制坦克的移动；
##### 增加游戏编号，改变两个游戏物体的控制键实现双人游戏。
#### *3）子弹*
##### 控制子弹的发射（即实例化子弹）：首先在坦克下创建空物体，将其固定于坦克发射处，通过代码使子弹实例在空物体处；
##### 控制子弹的飞行和爆炸:为子弹添加刚体，并且添加速度，添加子弹的碰撞检测，当子弹碰到某个物体时增加子弹爆炸特效。
#### *4）炸弹对坦克的伤害*
##### 碰撞检测，当子弹碰撞到坦克上坦克血量在10到20间随机减少，当血量减少为0时，该坦克消失。
#### *5）相机跟随*
#### 控制相机在两坦克之间跟随，并随坦克的移动放大或缩小，使两坦克始终在相机视野之内。
#### *6）音效*
##### 游戏整体音效：添加Audio Source属性，通过代码使得音效全程播放；
##### 坦克行动与静止的音效：在坦克移动脚本中添加音效，并在属性中赋值；
##### 子弹爆炸的音效：在坦克攻击的脚本中添加子弹爆炸的音效，并在属性中赋值。
#### *7）添加血条控制*
##### 在Hierarchy视图中添加UI slider，并且在坦克血量脚本中，当接受到坦克被攻击后，使得血条减少。
### *8）坦克大战仓库地址*
[github](https://github.com/Deviltxx/GameProjects)                                                  