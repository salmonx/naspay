# Discuz论坛积分支付插件
### 演示:
- 论坛用户名: nasfans 密码: 同用户名
- http://naspaydemo.nas123.xyz
### 特点:
* 基于区块链, 公开透明
* 无门槛限制, 无需审核认证
* 无任何手续费
* 配置简单

### 安装配置:
* 与普通插件安装相同, 下载项目解压到网站source\plugin\naspay目录
* 登录后台-应用-插件, 选择本插件,点击安装并启用
* 配置: 配置收款钱包账户,积分类型和兑换比例.
* 配置完成后点击"设置上链"保存配置信息


### 原理:
* 管理员配置积分商品信息并保存上链
* 论坛用户充值积分, 支付后请求后台确认
* 后台程序查询星云区块链支付信息,确认无误后增加该用户的积分


### 过程图解:
* 请看pics目录下截图
1. 站长后台安装启用插件后 进入插件页面配置钱包账号,积分类型,兑换比例
![1](https://raw.githubusercontent.com/salmonx/naspay/master/pics/1.png)
2. 配置完成后 站长需要将配置保存到区块链上
![2](https://raw.githubusercontent.com/salmonx/naspay/master/pics/2.png)
![3](https://raw.githubusercontent.com/salmonx/naspay/master/pics/3.png)
3. 配置结束后 前台用户即可点击"积分充值"进行充值
![4](https://raw.githubusercontent.com/salmonx/naspay/master/pics/4.png)
![5](https://raw.githubusercontent.com/salmonx/naspay/master/pics/5.png)
4. 充值成功后 用户将会收到通知, 并在"积分"栏目可以看到充值记录
![6](https://raw.githubusercontent.com/salmonx/naspay/master/pics/7.png)
5. 站长同样可以在后头看到充值记录 并可以进行补单等操作
![7](https://raw.githubusercontent.com/salmonx/naspay/master/pics/6.png)

