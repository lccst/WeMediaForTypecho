### WeMedia（自媒体）Typecho付费阅读插件（包含用户中心）（已支持免登录付费）
---

一个可以让Typecho站长使用付费阅读功能的插件，并且包含前台用户中心功能，适合各个自媒体用户使用的WeMedia（自媒体）Typecho付费阅读插件。

程序有可能会遇到bug不改版本号直接修改代码的时候，所以扫描以下二维码关注公众号“同乐儿”，可直接与作者二呆产生联系，不再为bug烦恼，随时随地解决问题。

<img src="http://me.tongleer.com/content/uploadfile/201706/008b1497454448.png">

#### 使用方法：
第一步：下载本插件，放在 `usr/plugins/` 目录中（插件文件夹名必须为WeMedia）；<br />
第二步：激活插件；<br />
第三步：填写配置；<br />
第四步：完成。

#### 使用注意：
此插件使用php5.6编写，php7.0“可能”会报语法错误，建议使用php5.6，因为7.0实在太高了=_=!

#### 与我联系：
作者：二呆<br />
网站：http://www.tongleer.com/<br />
Github：https://github.com/muzishanshi/WeMediaForTypecho

#### 遗留问题：
	浏览器兼容及极速模式兼容较差

#### 更新记录：
2019-01-27 V1.0.7

	1、去掉ispay、有赞支付，集成SPay微信支付；
	2、改变付费内容的添加方式为以下形式：
	
		<!--WeMedia start-->
		付费内容
		<!--WeMedia end-->
	
	3、增加后台文章列表条目数量；
	4、原用户中心评论页面使用Typecho系统自带的IP、代理函数；
	5、修改版本检测为异步检测等。
	
2018-12-24

	修复了因为cookie导致的第一次访问而不显示的错误及其他变量性质的错误。
	
2018-12-08

	新增免登录付费(支持任意文章在免登录/登录之间切换)

2018-09-21 
	新增了有赞支付支持微信、支付宝及网银支付
	修复了可通过审查元素修改价格的bug
	修复了针对老板typecho中内置时间函数失效的问题

2018-09-13 修复了可通过审查元素修改单价的bug

2018-07-28 新增评论积分和积分商城系统

2018-07-25 第一版本实现