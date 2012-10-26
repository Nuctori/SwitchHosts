#SwitchHosts!

 * Author: oldj
 * Email: oldj.wu@gmail.com
 * Blog: http://oldj.net/
 * Source: https://github.com/oldj/SwitchHosts
 * Latest Stable: 0.2.1.1780


这是一个用于快速切换 hosts 文件的小程序，基于 Python 和 wxPython 开发。


##功能特性：

 * 支持Common Host文件，切换到任意环境都将生效的host --- charlestang
 * 快速切换 hosts
 * 跨平台（基于 wxPython）
 * hosts 文件语法高亮
 * 可为不同的 hosts 方案设置不同的图标
 * 切换 hosts 方案时浮出窗口提示
 * 支持在线 hosts 方案
 * 方案档案可导入/导出


##下载地址：

你可以直接下载源码到本地运行或编辑，或者在下面下载可执行版本：

 * [SwitchHosts! Windows 绿色版下载](https://github.com/downloads/oldj/SwitchHosts/SwitchHosts_v0.2.1.1780.zip)
 * [所有下载](https://github.com/oldj/SwitchHosts/downloads)
 * [SwitchHosts! 支持Common Host版本 绿色版下载](https://github.com/downloads/charlestang/SwitchHosts/SwitchHosts.zip)


##程序截图：

以下为本程序的运行截图。

###Windows

![程序主界面](https://github.com/oldj/SwitchHosts/blob/master/screenshots/5.png?raw=true)

*程序主界面*


![系统托盘菜单](https://github.com/oldj/SwitchHosts/blob/master/screenshots/2.png?raw=true)

*系统托盘菜单*

###Mac

![程序主界面](https://github.com/oldj/SwitchHosts/blob/master/screenshots/3.png?raw=true)

*程序主界面*

![系统托盘菜单](https://github.com/oldj/SwitchHosts/blob/master/screenshots/4.png?raw=true)

*系统托盘菜单*

##更新历史：

 - 2012-10-09 增加 hosts 方案拖拽排序功能。
 - 2012-10-05 修复在中文目录下程序无法正常启动的问题。
 - 2012-09-30 初步完成 0.2.0 版。
 - 2011-12-14 允许输入超长的 hosts 方案。
 - 2011-10-09 发布 0.1.6 版，修复若干 bug，增加自动检查最新版本的功能。
 - 2011-09-29 发布 0.1.5 版，新增 hosts 内容语法高亮。
 - 2011-09-28 发布 0.1.4 版，新增“添加”、“删除”按钮；hosts 内容修改后自动保存；修改若干 bug。
 - 2011-09-19 发布 0.1.3 版，修复若干 bug。
 - 2011-09-15 发布 0.1.2 版，添加主面板，可以主面板上对 hosts 进行增加、删除、编辑、重命名等操作。
 - 2011-09-02 发布 0.1.0 版，完成基本功能。

##开发计划：

 - 增加选项配置界面
 - 自动监测当前使用的 hosts，如果有修改马上刷新
 - 可选择是否修改注册表以便让 IE 浏览器在修改 hosts 后马上更新
 - 增加快捷键
 - 备份系统初始 hosts


##已知问题

 - Hosts 编辑器中输入法有问题。


##版权及致谢：

 本程序的 Windows 版和 Mac 分别使用了 [ToasterBox](http://xoomer.virgilio.it/infinity77/main/ToasterBox.html) 和 [gntp](https://github.com/kfdm/gntp) 作为浮出提示解决方案，在此对作者的工作表示感谢！

 本程序完全免费，并基于 LGPL 协议开源。
