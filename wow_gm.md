符文护盾 .learn 41431 吸收50000伤害，提高施法和攻击速度100%，在这里我要重点提点下这个..BT到不能BT了..点了这个.所有技能瞬发,记住!所有!.包括生活技能也是一样.. 
灵魂震击 .learn 41426 远距离施法法术，近万伤害 
沸腾 .learn 41364 攻击速度提高100% 


.lookup item 沐圣 (你要查询的物品名,以T10套装为例)
.add  你的物品ID NPC也可以用同种方法刷

用法，进入游戏后按回车（聊天），进行输入
.additem 23162 背包
.modify money 999999999 给自己加金钱，后面空一格加数字，数字是以铜为单位的，要点下自己
.modify aspeed 10 改变玩家的速度 $num 数值是1到50
.revive        复活，先选中自己（可以用公会聊天模式输入 /g)
.die          杀死目标，
.gm off      GM模式关闭，怪物会主动攻击你。
.gm on       GM模式开启，打怪怪不打你 无敌状态
.levelup 84   为目标(或自己) 增加85级，数字自己调， (最好不要超过85 容易出错)
.learn all_myclass      学习自己的全部技能 （打完会卡一会） 法师学全部技能会看不到怪 用这个.unlearn 34426 因为学到隐身了 用下隐身技能在右上角右键取消就行
.learn all_mytalents    学会所有天赋
.additem                增加物品 
.modify hp x            增加目标的HP ，x处填当前HP和最大HP，中间有空格；例如自己加血需选中自己后，输入 .modify hp 222 9999
.modify mana x          修改法力值，使用同上
.die                    杀死所选中的NPC（声望点数要受影响）
.npc DEL                删除所选中物件（声望点数不受影响）
.gps              显示角色或生物的坐标(x,y,z) 地图标号和地区 
.announce         发布公告 
.go 16222.1 16252.1 12.5872 1             传送自己到GM岛
.bank            打开仓库

## 技能类

.maxskill   (所有技能熟练度增加满点)
.learn 31700 一个大黄蜂，可以在内域飞行 只有这一个能在内域飞，其它的就算能召唤也会掉下来
外域不能飞行，怎么回事 ??
答：可能是没学寒冷飞行
到达拉然去学下，或者输入命令 .learn 54197

## 物品类 
### 消耗品
.additem 21876 20格 原始月布包 
.additem 32837-8    埃辛诺斯战刃 
.additem 32863 +10坐骑速度 
.additem 32768 乌鸦 
.additem 32760 53秒伤箭 
.additem 32588 牛逼东西 banana  
.additem 18714 18格 箭袋 龙筋箭袋 
.additem 29118 18格 弹袋  18格+15%弹袋 虚空风暴 地精声望尊敬 
.additem 29143 18格 箭袋  18格+15%箭袋 "外域荆棘谷"——纳格兰 声望尊敬 
.additem 29144 18格 箭袋  座狼皮箭袋 
### 无等级装备 
.additem 22002-9 T0.5强化版 DZ 
.additem 31859 武器 
.additem 30973 手指 
.additem 18970 致命测试戒指 2 魔法致命+50%  

### T装
 
法师 　 　  
T1奥术师 .additemset 201  
T2灵风 .additemset 210  
T3霜火 .additemset 526  
T4占卜者 .additemset 648  
T5提里斯法 .additemset 649  
T6风暴 .additemset 671  
　 　 　  
牧师 　 　  
T1预言 .additemset 202  
T2卓越 .additemset 211  
T3信仰 .additemset 525  
T4化身（治疗） .additemset 663  
T4化身（战斗） .additemset 664  
T5幻身（治疗） .additemset 665  
T5幻化（战斗） .additemset 666  
T6赦免（战斗） .additemset 674  
T7赦免（治疗） .additemset 675  
　 　 　  
术士 　 　  
T1恶魔之心 .additemset 203  
T2复仇 .additemset 212  
T3瘟疫之心 .additemset 529  
T4虚空之心 .additemset 645  
T5堕落 .additemset 646  
T6凶星 .additemset 670  
　 　 　  
盗贼 　 　  
T1夜幕杀手 .additemset 204  
T2血牙 .additemset 213  
T3骨镰 .additemset 524  
T4虚空之刃 .additemset 621  
T5死神传承 .additemset 622  
T6刺杀者 .additemset 668  
　 　 　  
德鲁伊 　 　  
T1塞纳里奥 .additemset 205  
T2怒风 .additemset 214  
T3梦游者 .additemset 521  
T4玛洛尼(治疗) .additemset 638  
T4玛洛尼(平衡) .additemset 639  
T4玛洛尼(野性) .additemset 640  
T5诺达希尔（野性） .additemset 641  
T5诺达希尔（治疗） .additemset 642  
T5诺达希尔（平衡） .additemset 643  
T6雷霆之心（野性） .additemset 676  
T6雷霆之心（平衡） .additemset 677  
T6雷霆之心（治疗） .additemset 678  
　 　 　  
猎人 　 　  
T1巨兽之王 .additemset 206  
T2驭龙者 .additemset 215  
T3地穴追猎者 .additemset 530  
T4恶魔追猎者 .additemset 651  
T5裂缝行者 .additemset 652  
T6戈隆追猎者 .additemset 669  
　 　 　  
萨满 　 　  
T1大地之怒 .additemset 207  
T2无尽风暴 .additemset 216  
T3碎地者 .additemset 527  
T4飓风（治疗） .additemset 631  
T4飓风（法术） .additemset 632  
T4飓风（战斗） .additemset 633  
T4裂地（治疗） .additemset 634  
T4裂地（法术） .additemset 635  
T4裂地（战斗） .additemset 636  
T6破天（战斗） .additemset 682  
T6破天（治疗） .additemset 683  
T6破天（法术） .additemset 684  
　 　 　  
骑士 　 　  
T1秩序之源 .additemset 208  
T2审判 .additemset 217  
T3救赎 .additemset 528  
T4庇护（治疗） .additemset 624  
T4庇护（防御） .additemset 625  
T4庇护（惩戒） .additemset 626  
T5晶铸（治疗） .additemset 627  
T5晶铸（防御） .additemset 628  
T5晶铸（惩戒） .additemset 629  
T6光明使者（防御） .additemset 679  
T6光明使者（惩戒） .additemset 680  
T6光明使者（治疗） .additemset 681  
　 　 　  
战士 　 　  
T1力量 .additemset 209  
T2愤怒 .additemset 218  
T3无畏 .additemset 523  
T4战神(防御) .additemset 654  
T4战神(战斗) .additemset 655  
T5摧毁者（防御） .additemset 656  
T5摧毁者（战斗） .additemset 657  
T6冲击（战斗） .additemset 672  
T6冲击（防御） .additemset 673
 装备
战士 .additemset 656                         
骑士 .additemset 679             
萨满 .additemset 682
猎人 .additemset 669
德鲁伊 .additemset 676
盗贼 .additemset 668         
术士 .additemset 670
牧师 .additemset 674
法师 .additemset 671
法师 套装  35097 35096 35099 35098 35100 

圣骑士   T7  .additemset 789
法师     T7  .additemset 803
德鲁伊   T7  .additemset 798
萨满祭祀 T7  .additemset 795
牧师     T7  .additemset 804
术士     T7  .additemset 802
猎人     T7  .additemset 794
战士     T7  .additemset 788       
潜行者   T7  .additemset 801
死亡骑士 T7  .additemset 792 

T8                
.additemset 830  战士 
.additemset 837  术士
.additemset 824  萨满
.additemset 826  贼
.additemset 833  牧师
.additemset 821  圣骑士
.additemset 836  法师
.additemset 838  猎人
.additemset 829  德鲁伊
.additemset 835  死亡骑士

T9
.additemset 843 法师
.additemset 844 法师
.additemset 845 术士
.additemset 846 术士
.additemset 847 牧师
.additemset 848 牧师
.additemset 849 牧师
.additemset 850 牧师
.additemset 851 德鲁伊
.additemset 852 德鲁伊
.additemset 853 德鲁伊
.additemset 854 德鲁伊
.additemset 855 德鲁伊
.additemset 856 德鲁伊
.additemset 857 盗贼
.additemset 858 盗贼
.additemset 859 猎人
.additemset 860 猎人
.additemset 861 萨满
.additemset 862 萨满
.additemset 863  萨满
.additemset 864  萨满
.additemset 865  萨满
.additemset 866  萨满
.additemset 867 战士
.additemset 868 战士
.additemset 869 战士
.additemset 870 战士
.additemset 871 死亡骑士
.additemset 872 死亡骑士
.additemset 873 死亡骑士
.additemset 874 死亡骑士
.additemset 875 圣骑士
.additemset 876 圣骑士
.additemset 877 圣骑士
.additemset 878 圣骑士
.additemset 879 圣骑士
.additemset 880 圣骑士

风暴要塞橙色物品 
'30311'  '迁跃切割者' 
'30312'  '无尽之刃' 
'30313'  '瓦解法杖' 
'30314'  '相位壁垒' 
'30316'    '毁灭' 
'30317'  '宇宙灌注者', 
'30318'  '灵弦长弓' 
'30319'  '虚空尖刺' 

S5

.additemset 765 ZS 战斗
.additemset 766 QS 战斗
.additemset 767 DK 防御
.additemset 768 DK 战斗
.additemset 769 SM 法术
.additemset 770 SM 战斗
.additemset 771 SM 法术
.additemset 772 LR 
.additemset 773 D  治疗
.additemset 774 D 法术
.additemset 775 D 野性
.additemset 776 DZ
.additemset 777 MS法术
.additemset 778 MS治疗
.additemset 779 FS 
.additemset 780 SS 

s6 

.additemset 780  术士
.additemset 779  法师
.additemset 778  牧师
.additemset 777  牧师
.additemset 776  贼
.additemset 775  德鲁伊
.additemset 774  德鲁伊
.additemset 773  德鲁伊
.additemset 772  猎人
.additemset 771  萨满
.additemset 770  萨满
.additemset 769  萨满 
.additemset 768  dk
.additemset 767  圣骑士
.additemset 766  圣骑士
.additemset 765  战士

S8  用法  .add 代码

憤怒鬥士的辯護套裝 51474 51475 51476 51477 51479(圣骑士）
憤怒鬥士的救贖套裝 51468 51469 51470 51471 51473（圣骑士）
憤怒鬥士的震地者套裝 51503 51504 51505 51506 51508（萨满）
憤怒鬥士的雷霆之拳套裝 51509 51510 51511 51512 51514（萨满）
憤怒鬥士的戰鬥之潮套裝 51497 51498 51499 51500 51502（萨满）
憤怒鬥士的戰甲套裝 51541 51542 51543 51544 51545（战士）
憤怒鬥士的傳承套裝 51482 51483 51484 51485 51486（牧师）
憤怒鬥士的儀祭套裝 51487 51488 51489 51490 51491（牧师）
憤怒鬥士的戰鬥皮甲 51492 51493 51494 51495 51496（盗贼）
憤怒鬥士的戰衣套裝 51463 51464 51465 51466 51467（法师）
憤怒鬥士的魔化罩衣套裝 51536 51537 51538 51539 51540（术士）
憤怒鬥士的庇護套裝 51419 51420 51421 51422 51424（德鲁伊）
憤怒鬥士的狂野革甲套裝 51425 51426 51427 51428 51430（德鲁伊）
憤怒鬥士的獵裝 51458 51459 51460 51461 51462（猎人）
憤怒鬥士的褻瀆套裝 51413 51414 51415 51416 51418(DK)


  
T10代码

用法 .additem 代码

战士
沐圣依米亚领主战甲51225 
沐圣依米亚领主护手51226 
沐圣依米亚领主盔帽51227 
沐圣依米亚领主腿铠51228 
沐圣依米亚领主重肩甲51229

沐圣依米亚领主胸甲51220 
沐圣依米亚领主巨盔51221 
沐圣依米亚领主手甲51222 
沐圣依米亚领主腿甲51223 
沐圣依米亚领主肩铠51224

QS
沐圣光誓护胸51265 
沐圣光誓面甲51266 
沐圣光誓手甲51267 
沐圣光誓腿甲51268 
沐圣光誓肩卫51269

沐圣光誓手套51270 
沐圣光誓护胫51271 
沐圣光誓首盔51272 
沐圣光誓肩甲51273 
沐圣光誓外套51274 

沐圣光誓手套51275 
沐圣光誓护胫51276 
沐圣光誓首盔51277 
沐圣光誓肩甲51278 
沐圣光誓外套51279

LR
沐圣安卡哈血狩手甲51285 
沐圣安卡哈血狩首盔51286 
沐圣安卡哈血狩腿甲51287 
沐圣安卡哈血狩肩甲51288 
沐圣安卡哈血狩外套51289

dz

沐圣影刃胸甲51250 
沐圣影刃护手51251 
沐圣影刃盔帽51252 
沐圣影刃腿铠51253 
沐圣影刃肩铠51254

ms
沐圣赤红侍僧风帽 .additem 51255 
沐圣赤红侍僧裹手51256 
沐圣赤红侍僧披肩51257 
沐圣赤红侍僧束裤51258 
沐圣赤红侍僧衣饰51259

沐圣赤红侍僧手套51260 
沐圣赤红侍僧兜帽51261 
沐圣赤红侍僧护腿51262 
沐圣赤红侍僧长袍51263 
沐圣赤红侍僧肩垫51264

DK
沐圣天谴领主护胸51305 
沐圣天谴领主面甲51306 
沐圣天谴领主手甲51307 
沐圣天谴领主腿甲51308 
沐圣天谴领主肩铠51309

沐圣天谴领主战甲51310 
沐圣天谴领主护手51311 
沐圣天谴领主盔帽51312 
沐圣天谴领主腿铠51313 
沐圣天谴领主重肩甲51314 
SM
沐圣冰霜女巫肩卫51240 
沐圣冰霜女巫战裙51241 
沐圣冰霜女巫面甲51242 
沐圣冰霜女巫之握51243 
沐圣冰霜女巫护胸51244

沐圣冰霜女巫肩甲51245 
沐圣冰霜女巫腿甲51246 
沐圣冰霜女巫首盔51247 
沐圣冰霜女巫手甲51248 
沐圣冰霜女巫外套51249

沐圣冰霜女巫肩垫51235 
沐圣冰霜女巫褶裙51236 
沐圣冰霜女巫头盔51237 
沐圣冰霜女巫手套51238 
沐圣冰霜女巫鍊衫51239

fs
沐圣血法手套51280 
沐圣血法兜帽51281 
沐圣血法护腿51282 
沐圣血法长袍51283 
沐圣血法肩垫51284

ss
沐圣黑暗巫会手套51230 
沐圣黑暗巫会兜帽51231 
沐圣黑暗巫会护腿51232 
沐圣黑暗巫会长袍51233 
沐圣黑暗巫会肩垫51234 
xd 
沐圣棘织长袍51300 
沐圣棘织护手51301 
沐圣棘织盔帽51302 
沐圣棘织腿铠51303 
沐圣棘织肩铠51304

沐圣棘织头罩51290 
沐圣棘织手套51291 
沐圣棘织披肩51292 
沐圣棘织长裤51293 
沐圣棘织法衣51294

沐圣棘织缠手51295 
沐圣棘织护盔51296 
沐圣棘织腿甲51297 
沐圣棘织衣饰51298 
   
### 传送
#### 主城类

传送至 达拉然	.go 5780.27 667.56 756 571
1 传送到暴风城 .go -9065 434 94 0  
2 传送到铁炉堡 .go -5032 -819 495 0  
3 传送到达木纳苏斯 .go 9961 2055 1329 1  
4 传送到奥格瑞玛 .go 1317 -4383 27 1  
5 传送到雷霆崖 .go -1391 140 23 1  
6 传送到幽暗城 .go 1909 235 53 0  
7 传送到棘齿城 .go -977 -3788 6 1  
8 传送到藏宝海湾 .go -14302 518 9 0  
0 人类出生地 .go -8975.7 -138.1 83.4 0  
0 黑石山后门 .go -7319.7 -1086.1 277.0 0  
2 死亡矿井 .go -16 -383 62 36  
3 通灵学院 .go 199 126 135 289  
7 影牙城堡 .go -228.19 2110.56 76.88 33  
1 剃刀沼泽1 .go 1943 1544 82 47  
5 剃刀高地 .go 2592 1107 52 129  
7 祖尔法拉克 .go 1213 841 8.9 209  
9 GM之岛 .go 16222.1 16252.1 12.5872 1  
1 斯坦索姆 .go 3392 -3379 143 329  
4 黑翼之巢 .go -7671 -1106.6 397 469  
5 安其拉废墟 .go -8418.501953 1505.941162 31.823208 509  
6 安其拉 .go -8212.002930 2034.474854 129.141342 531  
8 翡翠森林 .go 3105.41 3096.78 27.0032 169  
9 时光巨洞 .go 3146.18 2312.06 -146.004 269  
11 艾尔文塔 .go -11037.7 -1999.49 92.9823 0  
12 海加尔山 .go 4603.946777 -3879.250977 944.183472 1  
13 神修道院 .go 16299.464844 16272.843750 69.443901 451  
.go -8913.23 554.633 93.7944 0 暴风城 （贸易区）  
.go -8951.62 524.373 96.6275 0 暴风城门口  
.go -8852.03 652.878 96.46 0 银行门口  
.go -8662.9 498.212 100.833 0 旧城区(白银之盾)  
.go -8635.62 762.727 103.667 教堂门口  
.go -8513.49 861.197 111.039 0 牧师训练师  
.go -9007.65 870.424 148.618 0 法师训练师入口  
.go -8896.36 834.148 99.5207 0 法师区法杖店旁  
.go -9043.76 -41.5906 88.3589 0 北郡山谷门口(人类出生地)  
.go -9092.38 -368.684 73.6163 0 北郡农场  
.go -9443.45 59.8944 56.0704 0 闪金镇  
.go -9355.84 537.441 52.5171 0 明镜湖边(暴风城右边)  
.go -9469.08 467.583 54.0913 0 明镜湖果园  
.go -9646.46 679.589 37.4136 0 西泉要塞  
.go -9964.72 391.509 35.6555 0 斯通菲尔德农场  
.go -9881.4 88.8972 33.3196 0 马科伦农场  
.go -9462.99 -161.312 60.7274 0 水晶湖  
.go -9769.82 -811.712 40.9564 0 布莱克威尔南瓜田  
.go -9549 -1407.04 54.7673 0 东谷伐木场  
.go -9136.28 -1053.89 70.624 0 英雄哨岗  
.go -9325.33 -1038.92 65.3535 0 石碑湖  
我只发那些比较有用的..垃圾的东东我就不弄出来了 
.aura 代码 艾泽拉斯飞行 32345 40120 

## 声望 
.learn 39474    声望:+500点星界财团声望         
.learn 39475    声望:+500点时间守护者声望     
.learn 39476    声望:+500点斯博格尔声望     
.learn 39460    声望:+500点塞纳里奥远征队声望 
.learn 39457    声望:+500点萨塔声望     
.learn 39456    声望:+500点阴郁城声望 

