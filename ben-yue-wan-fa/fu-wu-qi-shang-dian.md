# 🍠 服务器商店

* 服务器已经添加了商店，在主世界出生点往后走至折跃门可以进入（有鞘翅等工具可使用 **/res tp servershop** 前往）
* 商店使用<mark style="background-color:green;">**知识之书**</mark>为通用货币，部分场景下还可使用<mark style="background-color:green;">钻石块</mark>&#x20;
* 商店内可以兑换玩家头颅，装饰头颅，好玩的道具和高级装备等等，并且会持续更新新的道具，部分道具使用自研插件生成玩法

***

* 知识之书获取方式（价格随时变动，请以服务器为准）：

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

7 龙头 == 2 知识之书

128 试炼钥匙 == 1 知识之书

5 下界合金块 ==2 知识之书

3 otherside唱片 == 2 知识之书

2 pigstep唱片 == 1 知识之书

3 5号唱片 == 1 知识之书

2 Relic唱片 == 1 知识之书

3 回溯指针 =  1 知识之书

2 迅捷潜行Ⅲ 附魔书 == 1 知识之书



***

此外为了弥补知识之书不能堆叠和右键会消失的弊端，通过插件加入了知识之书的压缩和解压缩无序配方，并且商店也可以快速压缩/解压缩，压缩等级为耐久附魔等级，同时使用了自研插件防止右键知识之书和特殊头颅

<figure><img src="../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

以此类推，也可使用同等级书继续合成压缩等级更高的书，将一本压缩过的书放入工作台可解压缩

<mark style="color:red;background-color:orange;">**不同等级的书放入工作台合成/合成为超过4级的书会出错，目前没有解决办法，损失的书不补**</mark>

***

* 可用道具（更新于2024.3.23）（价格随时变动，请以服务器为准）：

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

1. 隐形展示框：放下展示框后不会显示框架，仍然可以正常放置并展示物品
2. 玩家的头：不带SkullOwner信息的头颅，作为头颅交易的占位符
3. 狂乱的鸡尾酒：成就完成药水，Lore中隐藏了药水效果，饮用后获得完成成就所需的全部药水效果1秒
4. 火焰弹：由自研插件实现的功能，右键可以发射
5. 风之法杖：\[灵感来自于插件[SlimeFun](https://github.com/Slimefun/Slimefun4)]由自研插件实现的功能，饱食度不为0时朝某一方向右键可以朝该方向移动，每次右键时会重置坠落距离
6. 咸鱼：击退棒，需要配合力量Ⅱ药水效果才可使用
7. 物品磁铁：\[灵感来自于插件[SlimeFun](https://github.com/Slimefun/Slimefun4)]由自研插件实现的功能，放置在物品栏任意槽位时按下蹲下键可将一定范围内的物品吸附至自己
8. 火焰弹：由自研插件实现的功能，拿在手上时可发射出去
9. 无限火力系列：包含副手，武器，使用时均不需要攻击蓄力，副手的无限火力需要放置在副手，否则不会生效
10. 末影箱扩容：使用后可扩大末影箱容积
11. 随身末影箱：使用后获得随身末影箱权限，使用 **/endersee** 打开末影箱
12. 刷怪笼采集镐：可采集刷怪笼，再次放置时可恢复其中的生物
13. 快速治疗：右键使用后立刻恢复所有生命值和饱食度并消耗物品，冷却时间90秒
14. 快速回城：右键使用后立刻回到main世界出生点，不消耗物品，冷却世界10秒
15. 2级装备：使用满配的附魔合金套加书兑换，属性好于满配附魔合金套
16. 3级装备：使用2级装备加书兑换，是目前服务器内能获得的最好装备，几乎对所有伤害都能减免80%

***

* 头颅商店（更新于2024.3.3）（价格随时变动，请以服务器为准）：

<figure><img src="../.gitbook/assets/image (6) (1) (1).png" alt=""><figcaption></figcaption></figure>

头颅商店支持定制，先到先得，定制时请发送正版id和希望设置的价格

只要是正常生存（不包括在商店获得的物品）下能获得的任何物品均可参与定价，价值大小随意（只要你觉得有人会买）

~~_目前没有考虑将购买头颅的成本移交给本人，以后也许会考虑（x）_~~
