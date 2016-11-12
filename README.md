# PoiPlayer
WordPress Plugins

又一款网易云外链播放器<br>
集成了音乐搜索功能，支持随机播放，进度条拖拉，支持Pjax或ajax站点全站播放。

最新版本：2.0.1<br>
更新摘要：<br>
2016-11-01<br>
-- 去除歌词Debug弹窗。<br>
-- 添加自定义歌曲搜索量。<br>
-- 添加自定义显示/隐藏音乐搜索框。<br>
-- 修复Pjax(Ajax)环境下搜索音乐刷新页面后跳回上一页的问题。

## 演示地址

[Acool博客](http://iacool.com/)  

## 使用方法

### 歌单

后台设置界面填写歌单或专辑ID获取数据，这些信息将会被保存到数据库，从而缩短页面的加载时间。

### 外链工具

新建页面添加短代码 [PoiMusic]

### 注意事项

搜索功能需要主机开启fsockopen()函数，否则无法读取数据，另外可能存在主机IP被墙而无法播放歌曲的问题，大多出现在海外IP的站点。
