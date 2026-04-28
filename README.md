VMware Workstation Pro 25H2官方版本界面默认是英文，需通过导入中文语言包实现汉化。

在[Release](https://github.com/Hermione027/VMware-Workstation-Full-25H2-zh_CN/releases/tag/Luo)中下载zh_CN.zip压缩包。

解压后把`zh_CN`文件夹复制到 VMware 安装目录下的 Message 文件夹里。

然后按Win+R打开`运行`窗口

输入
%APPDATA%\VMware\preferences.ini

编辑打开的preferences.ini文件

在文件最末端添加
pref.locale = "zh_CN"
然后保存文件即可

汉化文件取自VMware Workstation 17 Pro语言文件。
