# Surge自用配置文件

![](https://img.youtonghy.com/images/2022/05/08/f701835e7cb46.jpg)

鼠鼠自用的一套配置文件，根据本人使用习惯进行深度定制。

## 分流逻辑

通过域名及IP地址对策略组内容及中国大陆进行分流，其余走代理。

## 策略组

- 海外流媒体
- 苹果
- Microsoft
- Telegram
- Meta
- IP归属地
- 测速
- 广告
- 国家归属地

## 远程规则

远程规则来自互联网，感兴趣的可以通过地址自行查找出处。

## 如何导入？

有两个文件。一个是`模板.conf`，这个是给下面导入助手用的，需要填写证书，然后直接将证书写入配置文件导入。另一个是`模板（直接导入）.conf`，这个直接导入，将配置文件中`订阅链接`四字替换为你的node list即可使用，如果需要安装证书建议加在模块里面。

## Surge导入助手

做了一个捷径，方便各位导入使用。在最上面的文本里面输入证书，运行，在弹出窗口输入你的机场订阅地址，通过我的后端转化成node list（不安全，自行替换），然后导入Surge使用。
[https://www.icloud.com/shortcuts/e17ee0bd84824e2db1f7e917ba4b7458](https://www.icloud.com/shortcuts/e17ee0bd84824e2db1f7e917ba4b7458)

## 功能

目前功能仅保留谷歌中国转写，需要其他功能请自行通过模块添加。

## 最后

规则很多都是三三两两抄来的，感谢这些规则的原作者们，你们是真正的英雄。

欢迎star和fork

Github新手，请多多见谅

如果规则或者功能有问题，请联系我修补

个人网站：[https://youtonghy.com/](https://youtonghy.com/)

个人频道：[https://t.me/ythyx](https://t.me/ythyx)
