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
| C001 | Apple新闻 | Apple官方消息 | {{latest_content}}  |  [订阅地址](https://www.apple.com/newsroom/rss-feed.rss) |  
| <h2 id="互联网类">互联网类</h2> |  |   |  |
| H001 | 虎嗅 | 虎嗅网新闻 | {{latest_content}}  |  [订阅地址](https://www.huxiu.com/rss/0.xml) |  
| H002 | 36kr | 36氪 | {{latest_content}}  |  [订阅地址](https://www.36kr.com/feed) |  
| H003 | 微软亚洲研究院 | 微软亚洲研究院技术博客 | {{latest_content}}  |  [订阅地址](https://www.msra.cn/feed) | 
| H004 | 极客公园 | 极客公园  | {{latest_content}}  |  [订阅地址](https://www.geekpark.net/rss) | 
| <h2 id="金融类">金融类</h2> |  |   |  |
| F001 | 雪球 | 聪明的投资者都在这里,雪球每日精华 | {{latest_content}}  |  [订阅地址](https://xueqiu.com/hots/topic/rss) |  
| <h2 id="科技类">科技类</h2> |  |   |  |
| T001 | Hack News | 极其优质的极客新闻 | {{latest_content}}  |  [订阅地址](https://news.ycombinator.com/rss) |  
| T002 | 奇客Solidot–传递最新科技情报 | 奇客的资讯，重要的东西 | {{latest_content}}  |  [订阅地址](https://www.solidot.org/index.rss) |  
| T003 | 环球科学 | 科学美国人中文版，一些科普文章 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/huanqiukexue.xml) |
| T004 | MIT 科技评论 | MIT 科技评论 本周热榜 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/mittrchina/hot) |  
| T005 | 产品运营 | 产品运营 - 人人都是产品经理 | {{latest_content}}  |  [订阅地址](http://www.woshipm.com/category/operate/feed) |  
| T006 | 产品经理  | 产品经理 – 人人都是产品经理 | {{latest_content}}  |  [订阅地址](http://www.woshipm.com/category/pmd/feed) |  
| T007 | 产品100  | 产品人学习成长社区 | {{latest_content}}  |  [订阅地址](http://www.chanpin100.com/feed) |  
| T008 | 蓝卡  | 美好科技生活方式 | {{latest_content}}  |  [订阅地址](https://www.lanka.cn/feed) |  
| T009 | APPDO数字生活指南  | Simon的自留地_数码_App_羊毛_相机_数字指南 | {{latest_content}}  |  [订阅地址](https://simonword.com/feed) |  
| <h2 id="学习类">学习类</h2> |  |   |  |
| L002 | MOOC中国 | 慕课改变你，你改变世界  | {{latest_content}}  |  [订阅地址](https://www.mooc.cn/feed) |  
| <h2 id="学术类">学术类</h2> |  |   |  |
| A001 | 青柠学术 | 每个科研小白都有成为大神的潜力 | {{latest_content}}  |  [订阅地址](https://iseex.github.io/feed) |  
| <h2 id="生活类">生活类</h2> |  |   |  |
| L002 | 理想生活实验室 | 为更理想的生活 | {{latest_content}}  |  [订阅地址](https://www.toodaylab.com/rss) |  
| L003 | 一兜糖 | 家的主理人社区 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/yidoutang/index) |
| <h2 id="内容平台">内容平台</h2> |  |   |  |
| C001 | 知乎 | 知乎每日精选 | {{latest_content}}  |  [订阅地址](https://www.zhihu.com/rss) |  
| C002 | 湾区日报 | 关注创业与技术，每天推送3到5篇优质英文文章 | {{latest_content}}  |  [订阅地址](https://wanqu.co/feed/) |  
| C007 | HelloGitHub 月刊 | 一切出于兴趣。兴趣是最好的老师，HelloGitHub 就是帮你找到编程的兴趣。 | {{latest_content}}  |  [订阅地址](https://hellogithub.com/rss) |  
| <div id="C022" style="text-align: center;"><img src="./_media/favicon/C022.png" width="30px" style="width:30px;height: auto;"/><br><span>C022</span></div> | cnBeta.COM 精彩优秀评论 | 从cnBeta每天数千评论中精选出来的优秀评论 | {{latest_content}}  |  [订阅地址](https://www.cnbeta.com/commentrss.php) |  
| C028 | cnBeta | 中文业界资讯 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/cnbetatop.xml) |  
| C029 | China Daily News | 中国每日新闻 | {{latest_content}}  |  [订阅地址](http://www.chinadaily.com.cn/rss/cndy_rss.xml) |  
| C031 | CNU视觉联盟 | 每日精选 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/cnu/selected) | 
| C032 | 香水时代 | 最新香水评论-发现香水圈的新鲜事 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/nosetime/home) |  
| C033 | 恩山无线论坛  | 无线路由器爱好者的乐园 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/right/forum/31) |  
| <h2 id="游戏">游戏</h2> |  |   |  |
| <div id="G002" style="text-align: center;"><img src="./_media/favicon/G002.png" width="30px" style="width:30px;height: auto;"/><br><span>G002</span></div> | 游研社 |  无论你是游戏死忠，还是轻度的休闲玩家，在这里都能找到感兴趣的东西。 | {{latest_content}}  |  [订阅地址](https://www.yystv.cn/rss/feed) |  
| G003 | 游戏葡萄 |  深度解读游戏  | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/gamegrape/13) |  
| <h2 id="资源类">资源类</h2> |  |   |  |
| <div id="R001" style="text-align: center;"><img src="./_media/favicon/R001.png" width="30px" style="width:30px;height: auto;"/><br><span>R001</span></div> | 书格 |  有品格的数字古籍图书馆 | {{latest_content}}  |  [订阅地址](https://www.shuge.org/feed/) |  
| R002 | 书伴 |  为静心阅读而生 | {{latest_content}}  |  [订阅地址](https://feeds.feedburner.com/bookfere) |  
| <h2 id="Telegram优质频道RSS订阅">Telegram优质频道RSS订阅</h2> |  |   |  |
| TG005 | 书和读书 |  好书推荐。 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/GoReading) |  
| TG011 | Newlearnerの自留地 | 不定期推送 IT 相关资讯 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/telegram/channel/NewlearnerChannel) |



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

