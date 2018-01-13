# 冲顶大会辅助答题（PHP版）


## 版本记录
### 第一个版本（QH.php）
#### 使用PhpStorm的PHP Script运行<br>

1、先打开菜单Run->Edit Configurations选项<br>
2、然后在打开的窗口中点击左上角的+号<br>
3、在打开的菜单中选择PHP Script<br>
4、在打开的界面中找到Configuration->File<br>
5、选择你要在控制台运行的文件<br>
6、填入工作目录的路径（可填可不填），完成配置后点击右下角的OK<br>
7、回到主界面，点击菜单Run->Run...<br>
<br>
直接运行<br>
在控制台可以看到输出结果<br>
![](https://github.com/xbw12138/ChongDingDaHui/blob/master/image/QQ20180112-164550%402x.png)

#### 使用终端
直接php QH.php即可

-------

### 第二个版本（QH.php）
整合Mpush推送服务<br>
将结果直接推送到手机<br>
下载大会辅助APK，只有安卓版
[安卓端下载](https://fir.im/r3v5)
![](https://github.com/xbw12138/ChongDingDaHui/blob/master/image/Screenshot_20180113-141502.png)

-------

### 第三个版本（writeQuestion.php）
动态写入题目到txt文件中<br>
手动复制到百度搜索<br>
自行判断<br>


-------
### 第四个版本（QH.php）
根据题目描述加选项进行百度搜索<br>
提取百度搜索结果数量，数量最多的最接近答案<br>


-------

## 测试记录
#### 1月12日17点实测
尴尬的不行
错了至少……
尴尬的不行
![](https://github.com/xbw12138/ChongDingDaHui/blob/master/image/QQ20180112-173220@2x.png)

-------

#### 1月12日21点实测
`2.马来西亚的首都是？
["吉隆坡","马累","雅加达"]
结果统计:
吉隆坡       22
马累       0
雅加达       0
服务已经开始推送,请注意查收消息
.................................
3.中国的探月工程命名为？
["嫦娥工程","后羿工程","天宫工程"]
结果统计:
嫦娥工程       3
后羿工程       0
天宫工程       0
服务已经开始推送,请注意查收消息
.................................
4.京剧中，饰演性格活泼，开朗的青年女性的是？
["花旦","青衣","刀马旦"]
结果统计:
花旦       4
青衣       4
刀马旦       0
服务已经开始推送,请注意查收消息
...................................
5.电影《神偷奶爸》中的小黄人是格鲁的什么？
["亲戚","宠物","员工"]
结果统计:
亲戚       0
宠物       0
员工       0
服务已经开始推送,请注意查收消息
..............................
6.“玄武门之变”中，杀死李建成的是？
["李渊","李元吉","李世民"]
结果统计:
李渊       3
李元吉       10
李世民       23
服务已经开始推送,请注意查收消息
..................................................
7.周星驰的御用中文配音演员是？
["边江","石班瑜","童自荣"]
结果统计:
边江       0
石班瑜       13
童自荣       0
服务已经开始推送,请注意查收消息
....................................................
8.书本《我的前半生》是由哪位清朝皇帝撰写的自传？
["爱新觉罗·溥仪","爱新觉罗·载湉","爱新觉罗·载淳"]
结果统计:
爱新觉罗·溥仪       7
爱新觉罗·载湉       0
爱新觉罗·载淳       0
服务已经开始推送,请注意查收消息
........................................
9.中国别称“榕城”的是？
["四川成都","福建福州","广东广州"]
结果统计:
四川成都       0
福建福州       0
广东广州       0
服务已经开始推送,请注意查收消息
.................................
10.目前亚洲迪士尼乐园中占地面积最大的是？
["东京迪士尼乐园","香港迪士尼乐园","上海迪士尼乐园"]
结果统计:
东京迪士尼乐园       2
香港迪士尼乐园       3
上海迪士尼乐园       1
服务已经开始推送,请注意查收消息
...........................................
11.1980年的今天，湖南岳阳捕获了一条活体白鱀豚，经过人工饲养又存活了多少年？
["12年","15年","22年"]
结果统计:
12年       3
15年       1
22年       0
服务已经开始推送,请注意查收消息
.........................................................................
12.李清照的《如梦令》里的“绿肥红瘦”是描写什么季节的景象？
["晚春","盛夏","初秋"]
结果统计:
晚春       9
盛夏       4
初秋       3
服务已经开始推送,请注意查收消息`




