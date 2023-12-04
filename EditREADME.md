# Github Actions Rss (garss, 嘎RSS! 已收集{{rss_num}}个RSS源, 生成时间: {{ga_rss_datetime}})

信息茧房是指人们关注的信息领域会习惯性地被自己的兴趣所引导，从而将自己的生活桎梏于像蚕茧一般的“茧房”中的现象。

## 《嘎!RSS》🐣为打破信息茧房而生

![](./_media/ga-rss.png)

这个名为**嘎!RSS**的项目会利用免费的Github Actions服务, 提供一个内容全面的信息流, 让现代人的知识体系更广泛, 减弱信息茧房对现代人的影响, 让**非茧房信息流**造福人类~
[《嘎!RSS》永久开源页面: https://github.com/zhaoolee/garss](https://github.com/zhaoolee/garss)

## 推荐使用什么软件订阅RSS？
我推荐一款免费的浏览器扩展程序Feedbro ，使用教程[Chrome插件英雄榜第96期《Feedbro》在Chrome中订阅RSS信息流](https://www.v2fy.com/p/096-feedbro-2021-02-27/)

## 主要功能
1. 收集RSS, 打造无广告内容优质的 **头版头条** 超赞新闻页
2. 利用Github Actions, 搜集全部RSS的头版头条新闻标题和超链接, 并自动更新到首页,当天最新发布的文章会出现🌈 标志

邮件内容区开始>
<h2>新蒸熟{{new_num}}个小蛋糕🍰(文章) 生产时间 {{ga_rss_datetime}} 保质期24小时</h2>

{{news}}

<邮件内容区结束

## 已收集RSS列表

| 编号 | 名称 | 描述 | RSS  |  最新内容 |
| --- | --- | --- | --- |  --- |
| <div id="S006" style="text-align: center;"><img src="./_media/favicon/S006.png" width="30px" style="width:30px;height: auto;"/><br><span>S006</span></div> | 懒得勤快的博客 | 懒得勤快，互联网分享精神，勤于发现，乐于分享 |  {{latest_content}} | [订阅地址](https://masuit.com/rss) |
| S008 | 异次元软件世界  | 极具人气和特色的软件网站！专注于推荐优秀软件、APP应用和互联网资源，每篇图文评测都极其用心，并提供大量软件资源下载。 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/iplay/home) |  
| <h2 id="活着的个人独立博客">活着的个人独立博客</h2> |  |   |  |
| <div id="B005" style="text-align: center;"><img src="./_media/favicon/B005.png" width="30px" style="width:30px;height: auto;"/><br><span>B005</span></div> | 方圆小站 | zhaoolee的杂谈博客  | {{latest_content}} | [订阅地址](https://fangyuanxiaozhan.com/feed/) |
| <div id="B072" style="text-align: center;"><img src="./_media/favicon/B072.png" width="30px" style="width:30px;height: auto;"/><br><span>B072</span></div> | 数字移民 | 数字移民是一种生活方式 | {{latest_content}}  |  [订阅地址](https://blog.shuziyimin.org/feed) | 
| <div id="B073" style="text-align: center;"><img src="./_media/favicon/B073.png" width="30px" style="width:30px;height: auto;"/><br><span>B073</span></div> | Just lepture | Love its people, but never trust its government. | {{latest_content}}  |  [订阅地址](https://lepture.com/feed.xml) | 
| <div id="B078" style="text-align: center;"><img src="./_media/favicon/B078.png" width="30px" style="width:30px;height: auto;"/><br><span>B078</span></div> | 构建我的被动收入 | Lifelong Learner | {{latest_content}}  |  [订阅地址](https://www.bmpi.dev/index.xml) | 
| <div id="B121" style="text-align: center;"><span>B121</span></div> |  落园 |  专注经济视角下的互联网   | {{latest_content}} | [订阅地址](https://www.loyhome.com/feed/) |
| <h2 id="数码">数码</h2> |  |   |  |
| D001 | 少数派 | 少数派致力于更好地运用数字产品或科学方法，帮助用户提升工作效率和生活品质 | {{latest_content}}  |  [订阅地址](https://sspai.com/feed) | 
| D002 | 数字尾巴 | 分享美好数字生活 | {{latest_content}}  |  [订阅地址](https://www.dgtle.com/rss/dgtle.xml) | 
| D003 | Chiphell  | 分享与交流用户体验 | {{latest_content}}  |  [订阅地址](https://www.chiphell.com/portal.php?mod=rss)  | 
| H004 | 极客公园 | 极客公园  | {{latest_content}}  |  [订阅地址](https://www.geekpark.net/rss) | 
| <h2 id="金融类">金融类</h2> |  |   |  |
| F001 | 雪球 | 聪明的投资者都在这里,雪球每日精华 | {{latest_content}}  |  [订阅地址](https://xueqiu.com/hots/topic/rss) |  
| <h2 id="科技类">科技类</h2> |  |   |  |
| T001 | Hack News | 极其优质的极客新闻 | {{latest_content}}  |  [订阅地址](https://news.ycombinator.com/rss) |  
| T002 | 奇客Solidot–传递最新科技情报 | 奇客的资讯，重要的东西 | {{latest_content}}  |  [订阅地址](https://www.solidot.org/index.rss) |  
| T003 | 环球科学 | 科学美国人中文版，一些科普文章 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/huanqiukexue.xml) |
| T004 | MIT 科技评论 | MIT 科技评论 本周热榜 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/mittrchina/hot) |  
| <h2 id="内容平台">内容平台</h2> |  |   |  |
| C001 | 知乎 | 知乎每日精选 | {{latest_content}}  |  [订阅地址](https://www.zhihu.com/rss) |  
| C002 | 湾区日报 | 关注创业与技术，每天推送3到5篇优质英文文章 | {{latest_content}}  |  [订阅地址](https://wanqu.co/feed/) |  
| C003 | 爱范儿 | 让未来触手可及 | {{latest_content}}  |  [订阅地址](https://www.ifanr.com/feed) |  
| C004 | 小众软件 | 小众软件RSS | {{latest_content}}  |  [订阅地址](https://www.appinn.com/feed/) |  
| C005 | 199IT | 互联网数据资讯网 | {{latest_content}}  |  [订阅地址](https://www.199it.com/feed) |  
| C006 | IT之家 | IT之家 - 软媒旗下网站 | {{latest_content}}  |  [订阅地址](https://www.ithome.com/rss) |  
| C009 | WordPress大学 | WordPress建站资源平台 | {{latest_content}}  |  [订阅地址](https://www.wpdaxue.com/feed) |  
| <h2 id="游戏">游戏</h2> |  |   |  |
| <div id="G001" style="text-align: center;"><img src="./_media/favicon/G001.png" width="30px" style="width:30px;height: auto;"/><br><span>G001</span></div> | 机核网 |  不止是游戏 | {{latest_content}}  |  [订阅地址](https://www.gcores.com/rss) |  
| <div id="G002" style="text-align: center;"><img src="./_media/favicon/G002.png" width="30px" style="width:30px;height: auto;"/><br><span>G002</span></div> | 游研社 |  无论你是游戏死忠，还是轻度的休闲玩家，在这里都能找到感兴趣的东西。 | {{latest_content}}  |  [订阅地址](https://www.yystv.cn/rss/feed) |  
| G003 | 游戏葡萄 |  深度解读游戏  | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/gamegrape/13) |  
| <h2 id="资源类">资源类</h2> |  |   |  |
| <div id="R001" style="text-align: center;"><img src="./_media/favicon/R001.png" width="30px" style="width:30px;height: auto;"/><br><span>R001</span></div> | 书格 |  有品格的数字古籍图书馆 | {{latest_content}}  |  [订阅地址](https://www.shuge.org/feed/) |  
| R002 | 书伴 |  为静心阅读而生 | {{latest_content}}  |  [订阅地址](https://feeds.feedburner.com/bookfere) |  
| R003 | kindle吧 |  海量书单阅读分享者 | {{latest_content}}  |  [订阅地址](https://www.kindle8.cc/feed) | 
| R004 | 起点中文网 |  限时免费清单 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/qidian/free) | 
| <h2 id="Telegram优质频道RSS订阅">Telegram优质频道RSS订阅</h2> |  |   |  |
| TG001 | 4K影视屋 |  蓝光无损电影 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/dianying4K) |  
| TG002 | 编程笑话 |  程序员编程笑话 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/programmerjokes) |  
| TG003 | 薅羊毛 |  各种购物平台的优惠信息 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/yangmaoshare) |  
| TG004 | 竹新社 |  7×24不定时编译国内外媒体的即时新闻报道。 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/tnews365) |  
| TG005 | 书和读书 |  好书推荐。 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/GoReading) |  
| TG006 | 阿里云盘资源分享 |  分享资源完成阿里云盘任务，收获精品资源保存到不限速网盘 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/YunPanPan) |
| TG007 | Google Drive | 资源共享-软件-电影-纪录片-科学上网 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/YunPanPan) |



## 批量导入所有RSS订阅

OPML V2.0:  [https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v2.opml](https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v2.opml) 

OPML V2.0 备用CDN地址: [https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v2.opml](https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v2.opml)



> 如果RSS软件版本较老无法识别以上订阅,请使用[V1.0版本的OPML订阅信息](https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v1.opml) [V1.0版本的OPML订阅信息备用CDN地址](https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v1.opml)


## 如何定制自己的私人简报?

从 github.com/zhaoolee/garss.git 仓库, fork一份程序到自己的仓库

允许运行actions

![允许运行actions](https://cdn.fangyuanxiaozhan.com/assets/1630216112533FANcC1QY.jpeg)

在EditREADME.md中, 展示了zhaoolee已收集的RSS列表, 你可以参考每行的格式, 按行增删自己订阅的RSS

然后按照下图设置发件邮箱相关内容即可!

![](https://cdn.fangyuanxiaozhan.com/assets/1629970189283arACkBKe.png)

在根目录, tasks.json中配置收件人, 收件人是一个对象数组, 数组中的邮箱, 都会收到邮件, 后续会扩展更多功能~

```
{
    "tasks": [
        {
            "email": "zhaoolee@gmail.com"
        },
        {
            "email": "zhaoolee@foxmail.com"
        }
    ]
}
```

设置完成后 在README.md文件的底部加个空格，并push，即可触发更新！

## 无法收到邮件怎么办

可以按照以下代码，自测一下自己的HOST, PASSWORD，USER 是否能顺利发邮件

```
!pip install yagmail

import yagmail

# 连接邮箱服务器
yag = yagmail.SMTP(user="填USER参数", password="填PASSWORD参数", host='填HOST参数')

# 邮箱正文
contents = ['今天是周末,我要学习, 学习使我快乐;', '<a href="https://www.python.org/">python官网的超链接</a>']

# 发送邮件
yag.send('填收件人邮箱', '主题:学习使我快乐', contents)
```

在线自测地址 [Colab： https://colab.research.google.com/](https://colab.research.google.com/)

![在线自测](https://i.v2ex.co/zQWM0V6b.png)

## 发送邮件的效果

![手机端优化后的邮件效果](https://cdn.fangyuanxiaozhan.com/assets/163039979740967wCT8RQ.jpeg)

![PC端优化后的邮件效果](https://cdn.fangyuanxiaozhan.com/assets/1630399693988c2tk8n7k.png)

## 微信交流群 

[https://frp.v2fy.com/dynamic-picture/%E5%BE%AE%E4%BF%A1%E4%BA%A4%E6%B5%81%E7%BE%A4/qr.png](https://frp.v2fy.com/dynamic-picture/%E5%BE%AE%E4%BF%A1%E4%BA%A4%E6%B5%81%E7%BE%A4/qr.png)


## 广告位招租

![广告位招租](https://raw.githubusercontent.com/zhaoolee/ChineseBQB/master/README/zhaoolee-link.png)
