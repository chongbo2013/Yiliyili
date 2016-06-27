# Yiliyili
仿Android Bilibili客户端

项目介绍：仿Android Bilibili客户端编写，初始开发目的为Android开发课程大作业。

进度：
目前已大致实现第一层的UI，获取最热门番剧，以及播放功能。
正在研究如何RecyclerView的相关内容（包括如何使其高度自适应内容等等）

Signed-off-by: Alex-TangYH <937546209@qq.com>


# 更新日志:

###2016/06/26
1. 修改了获取最热门番剧的方法，主要内容为修改JSON解析方式，现可适应多参数获取
2. 修改了获取最热门番剧的接口方法名称及返回值（原先为bean，修改后为list＜bean＞

###2016/06/19
1. 将两张图片的名称修改为小写字母
2. 将项目上传自github/Alex-TangYH

###2016/06/15
大改动
1. 添加了一个数据获取方法以获取视频的cid
2. 给每个类添加了注释
3. 整理了包结构
4. 引入Vitamio库用于视频播放
5. 实现了基于Vitamio库的视频播放功能

###2016/06/14
1.添加了两个数据获取方法
2.番剧页面增加数据展示

###2016/06/13
将Banner中的一些方法提取到BannerUtils

###2016/06/11
在之前的基础上实现了
1. 分区界面
2.番剧的viewPager广告



