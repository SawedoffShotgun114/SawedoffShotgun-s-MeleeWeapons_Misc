<p>
  <img src="About/SS_Icon.png" height="128" align="left">
  <h1 align="right">SawedoffShot's Mechanoid_Combat</h1>
</p>

<p align="right">
  <a href="https://github.com/AlohaOe114/SawedoffShotgun-s-MeleeWeapons_Misc">
    <img src="https://img.shields.io/badge/-latest%20release-gray?style=for-the-badge&logo=github">
  </a>
  <a href="mailto:youngturksfree@outlook.com">
    <img src="https://img.shields.io/badge/-电邮%20联系作者-blue?style=for-the-badge&logo=mail">
  </a>
</p>


 - 自 20240826
 - 版本: 1.0.0.6 (支持 Rimworld 1.5/1.4)

# 描述

 一个 100% XML 的 Rimworld Mod，旨在添加一些可能适合现实生活和 Vanilla/CE 游戏环境的新近战武器。
 本Mod具体内容的"关键词"：
  “近战“

 "近战武器，小子" 

# 兼容性:
 游戏中途加入-安全    
 
 ==**!!CombatExtended(CE) Compatible/CE兼容!!**==    

 原版Core兼容    
 人物编辑器(CharacterEditor)(CE)兼容     
 CheatEngine(CE) 也许兼容    

# 特性：

 #### Vanilla，但有 CE 补丁：   
 - 充能长剑 (反飞螳(同时也可反蜈蚣)，较泛用，单手持握);   
   一把等离子长剑    
 - 充能德式大剑 (专业反蜈蚣，但对付非重装甲目标的效率低)    
   一把参考了古代某个经典武器的形制而做的等离子大剑 (比充能长剑还强，除了价格)    
 - 甩棍 (单手持握)    
   更灵活的棍棒，相较于钉头锤，其每击具有更低的冷却时间与更低的伤害，DPS比钢钉头锤略高。    
 #### CE独占：
 (占位符)


### 物品数据:
 基本数据：  
  原版数据：  

| 武器       | 质量       | 体积    | 锐器穿透(武器握柄/刺/劈砍) | 钝器穿透(武器握柄/刺/劈砍) | 冷却时间(武器握柄/刺/劈砍)   | 每击伤害(武器握柄/刺/劈砍)    | WTM(再除以60就是工作量) | 市场价值     | 平均每秒伤害    | 科技需求                                                                 |
|----------| -------- | ----- | --------------- |-----------------| ----------------- | ------------------ | --------------- |----------|-----------|----------------------------------------------------------------------|
| 铁长剑      | 2        | 8     | 13%/34%/34%     | -               | 2/2.6/2.6         | 9/23/23            | 18000/18000     | 225      | 8.6       | 长剑                                                                   |
| **甩棍**   | **0.55** | **1** | **-**           | **5.6%/13%**    | **1.2/1.2(head)** | **3.75/9.5(head)** | **10000/10000** | **103**  | **7.27**  | **机械加工**                                                             |
| **充能长剑** | **1.53** | **8** | **3%/60%/27%**  | **-**           | **1.5/1.38/1.22** | **4/18/40**        | **42000/42000** | **1920** | **29.08** | **电荷弹(如果在原版环境) / 动力近战武器Powered melee weapons(如果安装了"CE - 近战扩展"的mod)** |
| 铁钉头锤     | 1.25     | 3.5   | -               | 13%/24%         | 1.2/1.2(head)     | 9/15.7(head)       | 6000/6000       | 117      | 7.02      | 锻造                                                                   |

  CE数据：

| 武器                                                                   | 质量       | 体积    | 锐器穿透(武器握柄/刺/劈砍)                           | 钝器穿透(武器握柄/刺/劈砍)     | 冷却时间(武器握柄/刺/劈砍)   | 每击伤害(武器握柄/刺/劈砍)   | WTM(再除以60就是工作量) | 市场价值     | 平均每秒伤害    | 科技需求                                                                 |
|----------------------------------------------------------------------| -------- | ----- | ----------------------------------------- |---------------------| ----------------- | ----------------- | --------------- | -------- |-----------|----------------------------------------------------------------------|
| 铁长剑                                                                  | 2        | 8     | 2/0.72                                    | 1/1/3.24            | 1.78/1.78/1.64    | 4/18/40           | 18000/18000     | 225      | 16.54     | 长剑                                                                   |
| PoweredShortSword充能短剑(来自: CE - 近战扩展)(CE only)                        | 0.65     | 3.5   | 9.2/6.6                                   | 0.33/0.47/1.96      | 1.35/1.12/1       | 2/27/20           | -/32000         | 885      | 19.54     | 动力近战武器Powered melee weapons(如果安装了"CE - 近战扩展"的mod)                    |
| **充能长剑**                                                             | **1.53** | **8** | **15.4/11.05 (Can penetrate Armor Vest)** | **0.78/1.11/6.615** | **1.5/1.38/1.22** | **4/18/40**       | **42000/42000** | **1920** | **21.95** | **电荷弹(如果在原版环境) / 动力近战武器Powered melee weapons(如果安装了"CE - 近战扩展"的mod)** |
| **甩棍**                                                               | **0.55** | **1** | **-**                                     | **0.78/3.56**       | **1.2/1.2(head)** | **1.5/9.5(head)** | **10000/10000** | **103**  | **7.05**  | **机械加工**                                                             |
| 铁短剑                                                                  | 0.85     | 3.5   | 0.48/0.43                                 | 0.43/0.43/0.96      | 1.44/1.44/1.34    | 2/27/20           | 12000/12000     | -        | 14.65     | 锻造                                                                   |
| 铁钉头锤                                                                 | 1.25     | 3.5   | -                                         | 0.63/5.63           |                   |                   | 6000/6000       | 117      | 6.25      | 锻造                                                                   |
| 机械族巨剑(机械族/战棺 专武) (来自: SawedoffShotgun's Mechanoid_Combat) (玩家暂时无法获得) | 6.12     | 32    | 102.67/73.67                              | 5.2/7.33/44.1       | 1.5/1.38/1.22     | 16/72/160         | -               | 8330     | 80.58     | -                                                                    |


可能有剧透:

<span style="background-color:black;">    
（如果在 CE 环境中，“锐器暴击无视护甲”功能会使大部分动力锐器(除了PoweredShortSword(动力短剑)和更小的充能武器)的击杀蜈蚣的效率比PoweredMaul(充能大槌，属于"Combat Extended Melee" Mod)还高，（瞄准头部模式））。    
    
充能长剑 vs 充能德式大剑:    
击杀蜈蚣的速率: 7.5(长剑) / 10(德式大剑赢)    
杀飞螳速率: 3(长剑赢) / 2     
杀海盗(半数着防弹衣)速率: 2(长剑赢) / 1(德式大剑(使用砍身子瞄准模式，反正砍哪里都是一刀秒))    
</span>    


------------------------------------------

## 请注意:
作者玩CE玩的，可能不够熟悉原版环境

## 多语言:
- English
- ChineseSimplified
- ChineseTraditional

## FAQ: （常见问题解答）    
 Q1: CE compatible?/兼容CE吗?    
 A1: CE compatible./兼容CE ，而且一些物品是CE版独有的(也许作者以后会继续更新相关的物品)    

 Q2: 包括但不限于以下的贴图方面的问题: "贴图风格不统一", "贴图丑", 等等...    
 A2: 作者以后也许会优化的。 但现在，作者狠不得把114个小时掰成514个小时来用    

 Q3: 为何把充能类近战武器归类进电荷弹科技?    
 A3: 作者希望保持研究界面简洁而不愿定义太多研究项目。    

 Q4: 这些充能武器造价太贵了，有这钱我不如去买单分子剑呢    
 A4: 亲，这种充能武器能确保殖民地能够自行稳定量产高穿甲武器呢，毕竟有时不一定能买得到单分子剑什么的玩意呢。    

**（上文为“入门部分”。）
（如果这是您第一次使用此 mod，那您可以在此处停止阅读，然后去玩“边缘世界”了。**

------------------------------------------

## 已知问题:
 暂时未知(截至 20240916)

## 更新日志:
 - v1,0.0.6    
   新武器： 充能德式大剑（Zweihander）    
   更新优化，武器数据微调
 - v1.0.0.4     
   第一次于Github正式发布的版本    

 
## 作者的未来计划:
 (注：如果作者有更多时间的话，他希望先制作 “战棺 ”和 “单手武器”的内容。）    
 战棺：
  - （积压） 巨剑
  - （积压） 充能巨剑（）    
 单手：
  - （积压） 动力匕首    

 长杆武器（刺/砍）：（与戟相比的话：）    
  - （积压） 薙刀    
   （每击：伤害与穿甲更低；冷却时间更短）   
  - （积压） 长柄大刀    
   （每击：伤害与穿甲略高；冷却时间略长）    
  - （积压） 长柄斧    
   （每击：穿甲更高，伤害略高；冷却时间更长）   

 (以及 “长杆武器”中所有武器的充能版本）   

## 致谢:
 - **!! 感谢所有社区贡献者与社区享受者，和你 - 鼓励支持与bug反馈 !!**    
 - **[!! Combat Extended Melee（战斗扩展-近战武器） - 灵感来源之一 !! (点此访问他们的页面)](https://steamcommunity.com/sharedfiles/filedetails/?id=1924933379)**    

## 关于作者们:
 - SawedoffShotgun

## 版权/许可:
 Rimworld is owned by Tynan Sylvester.    
 <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><span property="dct:title">CEHDDPS</span> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="http://mailto:youngturksfree@outlook.com">SawedoffShotgun</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-ND 4.0 (Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License)<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1" alt=""></a></p>    

## 联系方式: (如遇问题，请联系作者电子邮箱)
 联系方式:  
  [电子邮件Email(主要方式): youngturksfree@outlook.com](mailto:youngturksfree@outlook.com)    
  [Github: https://github.com/AlohaOe114](https://github.com/AlohaOe114)    
 Ludeon(官方论坛): SawedoffShotgun

## 另见:(其他作品)
 [SawedoffShotgun's Gun_Misc]()    
 [SawedoffShotgun's MeleeWeapons_Misc]()

## 如果您喜欢我的作品
(也许能鞭策作者能进行一个更肝更快的更新)        
~~[如果您喜欢我的作品，那么能否帮我点杯ko-fi]~~      
~~[爱发电]~~      
~~[Patreon]~~

暂不接委托


![Preview](/About/Preview.png)