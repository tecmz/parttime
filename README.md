# 魔众人才招聘系统

魔众人才招聘系统系统采用PHP+Mysql架构,是一款对SEO非常友好、功能全面、安全稳定、支持多终端展示并且使用起来极其简单的多城市系统。

## 运行环境


```
操作系统
Linux/Unix 或  Windows
软件环境
Laravel 5.1的运行环境
Apache/Nginx , PHP 5.5.9+ / PHP 7.0 , MySQL 5.0+
```

## 系统截图


### 

![](https://mz-assets.tecmz.com/data/image/2020/05/19/49432_mrhr_6024.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/05/19/49433_vnms_5640.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/05/19/49433_rf84_8519.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/06/23/22125_naon_1441.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/06/23/22125_w174_4536.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/06/23/22126_uxda_2708.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/06/23/22126_5pmu_1960.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/06/23/22127_bbpi_9109.png)


### 

![](https://mz-assets.tecmz.com/data/image/2020/06/23/22127_0deo_1392.png)



## 版本迭代



### V2.1.0

**发布时间**：2020-07-03

- [新功能] 增加微信授权登录代理，解决多域名共用微信号问题
- [新功能] 后台增加常见安全设置问题校验
- [新功能] 富文本视频增加哔哩哔哩支持
- [新功能] 注册页面右侧增加授权登录操作
- [新功能] 增加&ldquo;使用说明&rdquo;和&ldquo;安装说明&rdquo;中英文版
- [系统优化] 高级表格显示宽度计算错位优化
- [系统优化] 微信扫码支付优化字段，去除无用配置字段
- [系统优化] 微信PC登录Proxy跳转兼容
- [系统优化] 微信授权登录方式修改为直接跳转（避免浏览器阻止弹窗）
- [系统优化] 优化支付账号与登录账号不一致问题
- [系统优化] 用户模块权限修复
- [系统优化] 后台表格显示优化
- [系统优化] 登录输入框自动补全关闭
- [系统优化] 注册、找回密码页面纯PC页面自适应显示优化
- [系统优化] 通过邮箱找回密码文案调整
- [系统优化] 后台管理页面底部浮动操作移动显示优化
- [系统优化] 优化config:cache缓存配置信息
- [系统优化] 备案网站链接修复
- [Bug修复] 富文本在Dialog中工具栏浮动定位问题修复
- [Bug修复] 修复多图上传链接被重置问题
- [Bug修复] 微信支付成功跳转链接修复



### V2.0.0

**发布时间**：2020-06-18

- [新功能] Feature 文件选择器增加分类搜索功能
- [新功能] Feature 统计代码可设定head或body
- [新功能] Bugfix 演示账号可修改后台文件
- [新功能] 系统初始化安装程序兼容HTTPS
- [新功能] 安装帮助文档升级，更友好的信息展示
- [新功能] 用户前后台全面升级
- [系统优化] 后台操作优化为文字按钮显示
- [系统优化] 注册、找回密码手机/邮箱验证码发送频率限制优化
- [系统优化] 手机编辑器图片预览为Contain模式
- [系统优化] 安装引导程序检测超时时间优化
- [系统优化] 安装&ldquo;Rewrite规则错误&rdquo;智能排查诊断
- [系统优化] 页面刷新链接优化（兼容微信页面不能刷新问题）
- [系统优化] 升级禁用create_function函数
- [系统优化] 后台优化手机显示，管理更加便捷
- [系统优化] 用户资料、绑定手机/邮箱页面优化
- [Bug修复] 修复HTTPS循环跳转问题
- [Bug修复] 未验证手机/邮箱绑定时问题修复
- [Bug修复] CMS快速编辑错误问题修复
- [Bug修复] 手机图片管理上传图片修复



### V1.6.0

**发布时间**：2020-03-01

- [新功能] Bugfix 文字过滤类purifier不存在
- [新功能] Feature 修改几处样式
- [新功能] Feature 升级后台界面
- [新功能] Feature 发布简历信息二级地区为非必须
- [新功能] Feature 发布兼职信息二级分类为非必须
- [新功能] Bugfix 修复PHP7.0 Cms调用错误



### V1.5.0

**发布时间**：2019-08-28

- [新功能] Feature 增加IIS伪静态文件web.config
- [新功能] Feature 引导安装提示用语不当
- [新功能] Feature 安装Exif扩展判断
- [新功能] Feature 头像PNG支持
- [新功能] Feature 增加网站风格设置
- [新功能] Bugfix 发布工作定位
- [新功能] Bugfix 后台职位管理审核
- [新功能] Feature 引导安装程序添加PHP7支持



### V1.4.0

**发布时间**：2019-06-06

- [新功能] Feature 增加安装依赖函数检测
- [新功能] Bugfix 修复member_oauth表不存在
- [新功能] Bugfix 修复用户图片弹窗错误
- [新功能] Bugfix 修复一处业务查询逻辑错误
- [新功能] Bugfix 修复搜索不起作用
- [新功能] Bugfix 修复alert弹窗确定按钮聚焦
- [新功能] Bugfix 修复后台不能自动升级
- [新功能] Feature 安装检测增加Fileinfo和PDO Mysql驱动
- [新功能] Feautre 后台搜索列表Select调整
- [新功能] Bugfix 修复后台帖子跳转路径错误
- [新功能] Feature 第三方登录报错统一处理
- [新功能] Feature 后台图片素材管理增强



### V1.3.0

**发布时间**：2019-03-31

- [新功能] Feature 优化懒加载显示为白色
- [新功能] Feature 增加富文本编辑器视频编辑
- [新功能] Feature 优化后台列表搜索显示
- [新功能] Feature 优化后台验证码显示



### V1.2.0

**发布时间**：2019-03-29

- [新功能] Feature 优化懒加载显示为白色
- [新功能] Feature 后台验证码显示优化
- [新功能] Feature 增加富文本编辑器视频编辑
- [新功能] Feature 优化后台管理搜索样式
- [新功能] Feature 增加QQ授权登录提示



### V1.1.0

**发布时间**：2019-03-19

- [新功能] Bugfix 修复登录页面页面错位
- [新功能] Feature 增加找回密码方式（手机和邮箱）
- [新功能] Feature 增加微博授权登录
- [新功能] Feature 增加QQ授权登录
- [新功能] Feature 增加微信PC扫码授权你登录
- [新功能] Feature 增加微信手机授权登录
- [新功能] Feature 增加返回顶部按钮



### V1.0.0

**发布时间**：2019-02-01

- [新功能] Release 1.0.0版本


## 演示地址

[http://parttime.demo.tecmz.com/](http://parttime.demo.tecmz.com/)

## 下载试用

[http://tecmz.com/product/parttime](http://tecmz.com/product/parttime)