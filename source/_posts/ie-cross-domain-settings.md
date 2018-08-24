---
title: IE11跨域检查跨域设置
date: 2018-08-23 10:20:10
tags:
---

IE11有安全设置中有两个选项，

- 跨域浏览窗口和框架
- 通过域访问数据源

如果上面两个选项被禁用，那么IE11会拒绝跨域请求。如果想要跨域成功，必须将上面两个选项设置为启用。


# 第一步

1. 打开IE11
2. 点击浏览器右上角的齿轮图标
3. 点击弹框上的 `Internet选项`

![](https://wdd-images.oss-cn-shanghai.aliyuncs.com/20180823102310_20uJ5k_Jietu20180823-102245.jpeg)

# 第二步

1. 点击`安全`
2. 点击`Internet`
3. 点击`自定义级别`

![](https://wdd-images.oss-cn-shanghai.aliyuncs.com/20180823103244_USZZfQ_Jietu20180823-103223.jpeg)

# 第三步

找到`跨域浏览窗口和框架`

如果这项是禁用的，那么要勾选启用。

![](https://wdd-images.oss-cn-shanghai.aliyuncs.com/20180823103506_t5pugZ_Jietu20180823-103456.jpeg)


找到`通过域访问数据源`

如果这项是禁用的，那么要勾选启用。

![](https://wdd-images.oss-cn-shanghai.aliyuncs.com/20180823103835_hDBxJg_Jietu20180823-103813.jpeg)

最后在点击确定。

![](https://wdd-images.oss-cn-shanghai.aliyuncs.com/20180823104124_nVXlJh_Jietu20180823-104111.jpeg)

最后，如果`跨域浏览窗口和框架`,`通过域访问数据源`都启用了，还是无法跨域。那么最好重启一下电脑。有些设置可能在重启后才会生效。