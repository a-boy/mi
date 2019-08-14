## 2019-08-08 四 立秋 微晴
不知不觉，已经是2019年的秋天了……

### Alpine Linux
Alpine 的意思是“高山的”，比如 Alpine plants高山植物，Alpine skiing高山滑雪、the alpine resort阿尔卑斯山胜地。

https://alpinelinux.org/ : “Small！Simple！Secure！Alpine Linux is a security-oriented, lightweight Linux distribution based on musl libc and busybox.”

### CSS Grid Layout
```
.wrapper {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-auto-rows: 200px;
}
```
CSS网格布局和弹性盒(flex)布局的主要区别在于弹性盒布局是为一维布局服务的（沿横向或纵向的），而网格布局是为二维布局服务的（同时沿着横向和纵向）。

嵌套网格节:一个网格元素可以也成为一个网格容器。

### DOS Defender game
DOS Defender is an x86 real mode DOS game   https://github.com/skeeto/dosdefender-ld31  
<img src="https://camo.githubusercontent.com/f61a0561342fda2acd362e3da8539b314ddccbfe/687474703a2f2f692e696d6775722e636f6d2f4235386f6773472e676966">

## 2019-08-10 六 阴
2019秋季开发者大书签。在浏览器里收集书签，这是一个很好玩的游戏，完全不亚于植物大战僵尸，比收集太阳花更丰富更有乐趣。我现在Firefox developer version 69.0b11 (32-bit)收集，因为firefox的Sidebar用起来比chromium方便些。首先在书签栏里建几个目录: java, python, html js css markdown, C, Android, games, music, video,!,...

## 2019-08-13 二 凌晨大雨 白天晴偏阴

IOI 2019——国际信息学奥林匹克竞赛，已经落下帷幕。
中国队四名选手，揽获三金一银，总冠军则再度被美国队华人选手摘走。
此次中国队选手全部第一次参赛，他们分别是：
钟子谦，福建省福州第三中学，获得金牌第4名；
杨骏昭，江苏省南京外国语学校，获得金牌第5名；
高嘉煊，中山市中山纪念中学，获得金牌第20名；
王修涵，四川省成都市第七中学，获得银牌第21名。
而今年的IOI冠军，再次被17岁的华人美国队员Benjamin Qi拿走。
至此，他已经连续获得两次IOI冠军，被网友称为“神犇”，从10岁时，父母就开始带他去参加数学比赛，开始展现出数学天才的一面。

第 30 届国际信息学奥林匹克竞赛（IOI 2018）于2018年9月1日至9月8日在日本筑波举行。
本次比赛中国队参赛选手分别为：
杨懋龙（长郡中学）、
朱震霆（安徽师范大学附属中学）、
陈江伦（长郡中学）、
任轩笛（绍兴市第一中学）
IOI 2018 创纪录的吸引了来自 87 个国家和地区的 341 多名信息学选手和 173 位团队领队参与。

## 2019-08-14 三 阴

mathpix  JChemPaint   Maple  Julia

```
curl -X POST https://api.mathpix.com/v3/latex \
    -H 'app_id: trial' \
    -H 'app_key: 34f1a4cea0eaca8540c95908b4dc84ab' \
    -H 'Content-Type: application/json' \
    --data '{ "url": "data:image/jpeg;base64,'$(base64 -i limit.jpg)'" }'
```

gookey : java , chemistry , molecule

海龟绘图 Lib/turtle.py     turtledemo    Tkinter GUI