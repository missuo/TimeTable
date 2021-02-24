# TimeTable
基于Bark的课表推送系统

## 写在前面

本项目是基于 [Bark](https://github.com/missuo/bark) 消息推送开发的。可以说没有Bark，我根本没办法完成这个项目。在此感谢「Finb」大佬。

### 由于现在还没有开学，我们的程序还在公测阶段，欢迎你们加入公测。

## 功能与优势

- [x] 支持iOS设备/M1 Mac
- [x] 锁屏状态推送
- [x] 提前推送
- [x] 绝不接入广告
- [ ] 情侣课表/多人课表（正在开发）
- [ ] 生日祝福（后续会支持）
- [ ] 紧急通知（后续会支持）
- [ ] 支持安卓设备（由于Bark开发的局限性）

## 使用方法

1. 在App Store下载 「Bark」，如果不知道怎么下载，你可以点击 「[这里](https://itunes.apple.com/cn/app/bark-customed-notifications/id1403753865)」前往安装。

![AppStore截图](https://telegraph.work/file/f4be6979af9494d12abbd.png)

2. 打开App，点击中间的注册设备，弹出是否允许通知，点击「允许」。 

3. 点击右上角的「+」号，输入 https://push.nisekoo.com ，然后点右上角的「√」。

![配置服务端](https://telegraph.work/file/5bcac8dee0860254af84e.png)

4. 返回到主界面之后，你可以看到一串链接，点击右上角的「复制」按钮，复制你的密钥。

![复制密钥](https://telegraph.work/file/bcf71b71e12e5897eee4f.jpg)

5. 前往 https://kb.nisekoo.com ,订阅课表推送。如果你懒得复制，可以点击「[这里](https://kb.nisekoo.com)」，或者扫描下方二维码。

![二维码](https://telegraph.work/file/362cc1c46226fcdd4e631.png)

6. 接着填写你的账号密码，粘贴你的密钥，点击「订阅」即可。

![截图](https://telegraph.work/file/3500b0192109b097be5e2.png)

## 功能预告

「情侣课表」我们会在不久之后支持。让您能够不在TA身边，却可以在手机上实时收到她的上课信息。当然，为了安全，情侣课表的绑定是单向的，意味着你绑定了你的爱人，你可以收到你爱人的上课信息，但是相反，她收不到你的上课信息。如果想要双方都能收到，她也必须在她的账号绑定你。

「生日祝福」我们后期会考虑在数据库中记录每个用户的生日信息，将在用户生日的当天，给您推送一条生日祝福的消息。表达我们对用户的心意。

「紧急推送」我们将在某些紧急时刻，推送一些关键的通知。

「Bark」，原计划是采用微信的「服务号」，但是由于微信的服务号需要打开微信才能看到消息，我个人觉得不太方便，所以还是基于Bark搭建。

**后期我们会考虑基于「Bark」二次开发生成独立App，当然这可能还很遥远，我们要得到原作者的许可，才可以上架App Store。**

**安卓端可能永远不会支持（因为安卓端类似的软件太多了）**

**感谢你们的支持！你们的支持永远是我开发最大的动力**







