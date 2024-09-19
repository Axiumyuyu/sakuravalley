---
description: 邮件（礼包），侧边栏，玩家传送，挂机，动作等
---

# 🎄 基础插件

> 我懒得更新了.jpg

* <mark style="color:green;">邮件相关</mark>

服务器的补偿/奖励等主要通过邮件（礼包）发送

**/kit  <礼包名字>**   领取对应的礼包

**/kitlist** 查看所有礼包列表

***

* <mark style="color:green;">聊天相关：</mark>

聊天时附加前缀@ （或者指令**/global <消息>**）可以发送全局消息，所有人均可见

前缀! （注意为英文叹号或者指令**/local <消息>**）可发送附近消息，默认仅周围10方块距离内的玩家可看到消息

**/tell <玩家名> <消息>** 可单独给某玩家发送私信

在聊天消息中加入<mark style="color:blue;">`@hand`</mark> 可以将手中物品展示给其他人



***

* <mark style="color:green;">Tab列表相关：</mark>

<figure><img src="../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

Tab列表中，不在本子服的玩家名显示为_<mark style="color:blue;">蓝色下划线斜体字体</mark>_

在本子服的显示为正常字体并带有当前延迟，所在世界前缀以及当前生命值

其他子服也是如此

***

* <mark style="color:green;">侧边栏相关：</mark>

<figure><img src="../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

可以使用 **/scoreborad**  关闭或开启侧边栏

***

* <mark style="color:green;">玩家传送相关：</mark>

**/rtp   （或/wild）**   随机传送

&#x20;  传送范围为100-3000方块

&#x20;  末地，下界维度以及部分世界不可用

**/tpa <玩家名>**   请求传送到某玩家身边

**/tpi** **<玩家名>**   请求某玩家传送到你身边

**/tpyes**   接受传送请求（也可直接点击聊天栏里的按钮）

**/tpno**   拒绝传送请求（也可直接点击聊天栏里的按钮）

请求将会在60秒后过期

***

* <mark style="color:green;">动作相关：</mark>

**/sit**   坐下

&#x20;  同样可空手点击台阶下半部分/楼梯/地毯

> **请注意，该动作不会检测上方有无方块阻挡，因此空手点击坐下时可能会导致窒息**

**/hat**   将手中物品戴到头上

***

* <mark style="color:green;">便捷指令：</mark>

**/condense**   快捷合并背包中可合并物品（如金粒->金锭->金块，木棍→梯子）

***

* <mark style="color:green;">AFK相关：</mark>

**/afk**   立刻进入/解除挂机状态

&#x20;  玩家在保持1分钟没有动作时将会自动进入挂机状态，进入挂机状态后产生持续1秒以上的动作（包括移动视角，与/被方块或实体交互，）将会解除挂机状态
