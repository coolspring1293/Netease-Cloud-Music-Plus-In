--- coolspring1293 forked from https://github.com/bigfa/nm --
--- Thanks a lot to the author --
--- I use the code only for fun and PHP learning --- 
--- Thank you again! --- 


=== Netease Music ===
Contributors: bigfa
Tags: wordpress, 163,music ,网易云音乐, 虾米音乐
Requires at least: 4.0
Tested up to: 4.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

网易云音乐

== Description ==

已修复网易封锁海外IP的问题。

演示地址:https://galfond.com/music

插件使用帮助：https://fatesinger.com/74369

== Installation ==

1. 上传 `neatease-music`目录 到 `/wp-content/plugins/` 目录或后台搜索netease music
2. 在后台插件菜单激活该插件
3. 后台填写你的网易云音乐用户ID
4. 直接使用短代码[nm]，或者在需要的地方使用插入`netease_music()`，或者在插件设置页面直接选择页面


== Frequently asked questions ==

网易云音乐资源均为http资源，如果你是整站https，则会出现小黄锁。

== Changelog ==
= 2.0.10 =
* 错误修复
* 增加自定义CSS功能

= 2.0.9 =
* 增加一个播放器宽度控制选项
* 添加了数据异常时的警示信息
* 细节优化

= 2.0.8 =
* 增加一个是否显示喜欢的音乐选项

= 2.0.7 =
* 修复海外服务器无法播放单曲的问题

= 2.0.6 =
* 增加自定义歌单功能

= 2.0.5 =
* 修复后台设置无法修改id的bug

= 2.0.4 =
* 增加虾米音乐支持

= 2.0.3 =
* 错误修复

= 2.0.2 =
* 错误修复
* 增加了歌曲热门评论

= 2.0.1 =
* 重写了歌单页面

= 2.0.0 =

* 重构了整个插件
* 增加了embed 音乐功能

= 1.9.1 = 
* 静态文件按需载入
* 删除了播放次数
* 合并了JS文件

= 1.9.0 = 
* 增加了flash支持，解决低版本浏览器无法播放。
* JS代码优化
* 部分CSS样式修正

= 1.8.0 = 
* 增加了播放次数
* 增加了内存缓存
* 部分CSS样式修正

= 1.7.0 = 
* 重写了JS部分
* 部分CSS样式修正
* 歌曲列表加入了时间显示

= 1.6.0 = 
* 采用AJAX方式加载更多专辑
* 部分CSS样式修正
* 增加了一个后台直接选择页面的方法
* 删除了单曲短代码
* 移除了无用JS文件

= 1.5.3 = 
* 部分CSS样式修正
* 点击专辑封面可以暂停播放

= 1.5.1 = 
* 修改了播放器的代码位置，避免和文章列表样式冲突
* 修改默认缓存时间为1周
* 部分CSS样式修正

= 1.5.0 = 
* 添加单曲播放器
* 精简了JS文件
* 部分CSS样式修正

= 1.4.0 = 
* 添加了歌词同步的选项
* 添加了播放条
* 添加了歌曲控制按钮
* 添加了专辑封面图宽度设置选项
* 隐藏了默认歌单（用户喜欢的歌曲）

= 1.3.0 =
* 增加了专辑封面大小选择
* 播放列表单双列选择

= 1.2.0 =
* 增加后台设置选项
* 添加数据缓存

= 1.1.0 =
* 调用Wordpress 自带jquery库

= 1.0.0 =
* 最初0.0.1版本发布

== Upgrade notice ==
