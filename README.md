# Latern
Latern installer only for personal usage.

## 蓝灯(Lantern)最新版本下载  Download Lantern 

[Windows 7及以上系统](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer.exe)      [备用地址 Alternative address](https://s3.amazonaws.com/lantern/lantern-installer.exe)  

[安卓版(4.1+) Android(4.1+)](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer.apk)               [备用地址 Alternative address](https://s3.amazonaws.com/lantern/lantern-installer.apk)  [Google Play 下载 Download](https://play.google.com/store/apps/details?id=org.getlantern.lantern) 

[苹果电脑版(OS X 10.11 El Capitan及以上)](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer.dmg)               [备用地址 Alternative address](https://s3.amazonaws.com/lantern/lantern-installer.dmg) 

Ubuntu 14.04及以上[(32位系统)](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-32-bit.deb) [(64位系统)](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-64-bit.deb)

请大家收藏本页面，方便日后下载新版。
Bookmark this page to download the latest versions in the future.

**使用遇到问题，请阅读[蓝灯常见问题解决办法](https://github.com/getlantern/lantern/wiki) When you have a problem when using Lantern, please refer to [FAQ](https://github.com/getlantern/lantern/wiki)** 

**If you would like to give the latest but more UNSTABLE BETA versions a try, you can find all of them at the following links:** **如果希望试用最新测试版，请点击如下下载链接：**
- [Android](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-preview.apk)
- [Windows 7 and above](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-preview.exe)
- [OSX 10.10 and above](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-preview.dmg)
- [Ubuntu 14.04 32 bit](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-preview-32-bit.deb)
- [Ubuntu 14.04 64 bit](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-preview-64-bit.deb)

**第一次下载安装蓝灯时，请等待几分钟以便完成配置，笔芯**

**Please allow some time for Lantern to complete configurations if installing it for the first-time, love <3**



### 蓝灯常见问题解决办法

自行解决问题通常只需要几十分钟,管理员调查解决问题需要几天至几周。以下是问题自助解决方案，可以自行解决95%以上的问题。

卸载蓝灯，然后删除整个文件夹c:\Users<用户名>\AppData\Roaming\Lantern后，安装最新版

请使用管理员权限安装和启动。

Windows防火墙配置错误: 请把Windows防火墙关闭再重新打开，或者一直保持关闭。

系统配置错乱: 创建一个新的Windows用户后，在这个新Windows用户下安装蓝灯最新版。控制面板-用户账户-管理账户-在电脑配置中添加新用户-将其他人添加到这台电脑。

蓝灯没有成功设置系统代理: 请打开蓝灯-设置-高级设置-管理系统代理-打勾。 Windows系统，请打开控制面板的Internet选项->连接->局域网设置->代理。手工把代理设成地址127.0.0.1，端口***。端口每个用户都不同，具体请见蓝灯-设置-高级设置里面显示的HTTP代理服务器端口。 Mac系统，请打开Safari-偏好设置-高级-更改设置（“代理”旁边）- HTTP代理 设成地址127.0.0.1，端口***。

确保系统时间正确，几小时也不能差。

请勿使用国产的杀毒软件，会干扰翻墙软件。

蓝灯与迅雷极速版冲突，请使用普通的迅雷。

host文件出错: Windows系统请删除 C:\Windows\System32\drivers\etc 下的host文件。Mac系统请删除 /private/etc/ 下的hosts文件

系统代理被篡改: 打开注册表编辑器，找到HKEY_CURRENT_USER/Software/Microsoft/Windows/CurrentVersion/Internet Settings 分支，把它下面以 Proxy 打头的键值对（如ProxyEnable，ProxyOverride，有的是ProxyServer）改名或全部删除。

将Lantern更新到最新版本，重启Lantern更新或到https://github.com/getlantern/lantern 下载手动更新。

Lantern续费后时间没更新：重启Lantern即可。

授权设备可以用如下方法： －在lantern界面左边菜单点击“授权设备使用专业版”，在里面输入购买时的邮箱，激活码就会发到你的邮箱，然后输入激活码即可； －在新设备选择“授权设备使用专业版”，该界面会收到验证码，然后请到专业版设备输入验证码。

建议使用chrome／firefox，不要用360这类浏览器。 如chrome不能用： 这种可能是chrome的代理被其他软件接管了，请到chrome://net-internals/#proxy 验证如下设置是否和lantern设置>高级设置里的一致。如果不一样，请检查软件或chrome的代理插件并修复。 Proxy server for HTTP: Proxy server for HTTPS:

如firefox不能用： 到设置里把代理改为“使用系统代理”

其他：不要使用乱七八糟的系统清理软件，可能会造成系统配置错乱。这样的情况只能重装系统，推荐Windows 10或者MacOS Mojave。微软已经不支持XP系统。

自行解决问题通常只需要几十分钟,管理员调查解决问题需要几天至几周。 若各位无法按照本帖自行解决，愿意等待管理员人为调查的，请在应用内报告问题。
