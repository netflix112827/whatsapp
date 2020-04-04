# whatsapp
对于一个高度安全的通信软件Whatsapp来说，在中国大陆无障碍地使用是非常困难的。如果你是苹果用户，那么你很幸运，只要严格按本站教程设置，你就能享受安全的通信环境了。但如果你是国产安卓手机，你就悲剧了，你是很难流畅地使用Whatsapp的，尤其是那些华为手机用户，华为手机以不安全和不稳定著名，要流畅地使用安全的通信软件是件很难的事情。
但在现实生活中，大部分人对手机安全不了解，有些人仅偶尔使用Whatsapp，很少人会因为安全而更换手机的。这里提供一个折衷的方案，严格按本教程操作，你就能在华为手机上较流畅地使用Whatsapp，本文仅以华为P8为例进行说明，不同手机的设置不一样，但原理是一样的（如有疑问请在评论区留言）。

第一步：设置好代理软件
强烈推荐使用kitsunebi软件，因为它在即时通话时很流畅，而V2rayNG通话很卡。有了代理软件，当然还得安装Whatsapp软件，上面的教程都有详细说明。

第二步：安装Push Notifications Fixer
由于华为手机长期黑屏以后，Whatsapp是无法收到信息的，这个是无解的，因为华为不给Whatsapp等安全通信软件很高的权限，反而给了世界上最不安全的通信软件微信很高的权限。Push Notifications Fixer软件的作用是定时让系统检查Whatsapp有没有来信息，下载安装的办法是：在开启代理软件的时候，用Google搜索“Push Notifications Fixer APK”在apkpure.com这个安全的网站下载这个软件并安装，在没有Google play商店的大陆手机上通过这种方式安装是最安全的。开启后，将“Mobile heartbeat interval”和“WiFi heartbeat interval”设定为1分钟，也就是说华为手机尽管无法实时使用Whatsapp，但通过这个软件可以把延迟控制在1分钟，选择好后请点击“Apply Settings”确认，具体见下面的图片：
第三步：关闭华为手机的电池管理
因为电池管理会在后台自动杀死kitsunebi软件、Push Notifications Fixer和Whatsapp，这些软件被杀死以后，你就无法正常使用Whatsapp了。点击手机“设置”——“电池”——“启动管理”，把上面三个软件都设置为“手动管理”，并勾选“允许自启动”和“允许后台活动”。具体见下面的图片：
第四步：关闭高耗电提醒并给予高权限
华为手机总是错误的给予kitsunebi软件、Push Notifications Fixer和Whatsapp高耗电提醒，我们需要手动关闭，并给予高的权限，否则Whatsapp信息是无法及时接收的，点击手机“设置”——“应用和通知”——“权限管理”，分别找到kitsunebi软件、Push Notifications Fixer和Whatsapp这个三个应用，并关闭“高耗电提醒”，最后给予Whatsapp高的通知和应用权限，具体见下列图片
具体教程请访问：blog.zfast.in
