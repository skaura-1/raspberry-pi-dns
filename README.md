# 树莓派做 DNS 服务器以及网关，实现自由上 Google
首先声明，本教程的实验环境为树莓派，理论上只要是 Linux 系统就可以，可能细节步骤有所差别，本教程用到的所有软件均来源于网络，请用户自行判断风险。教程仅限于交流学习，禁止用于非法用途。



## 服务器配置

首先，我们想要上 Google，需要有一个可以上 Google 的服务器，我们就可以通过服务器中转来访问 Google YouTube 等网站。



如果你已经有服务器了并配置好 v2ray 软件，可以忽略下面的链接。如果你还没有一个能访问 Google 的服务器，这里器推荐 Vultr，本人测试访问 Google YouTube 等国外主流网站的速度很快，价格也比较合理。

[Vultr 注册以及创建服务器安装配置 V2ray](./vultr.md)



## 树莓派配置

