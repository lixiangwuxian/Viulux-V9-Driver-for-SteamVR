# Viulux-V9-Driver-for-SteamVR

开源地址： [Viulux Driver](https://github.com/lixiangwuxian/Viulux-Driver)

将[Relativty](https://github.com/relativty/Relativty)驱动和[OpenHMD](https://github.com/OpenHMD/OpenHMD)缝合而成的Steam VR驱动。

**无人保证此驱动一定能正常使用，使用者应自己承担责任。**

~~可配合Relaivty的摄像头全身追踪。~~ 0.1.2版本之后移除了Relativty的人体识别部分代码，实现位置追踪只能使用Nolo套件

水平有限，Bug在所难免。

如果你没有Nolo套件，请下载v0.1.1版本。后续版本无法正常使用。

bug:

1. 启动时头显屏幕只会显示一片红色，重启SteamVR即可。
2. 启动时有时某个手柄不会显示。重启SteamVR直至两个手柄都能显示即可。
3. 系统键基本呼不出系统菜单。按键能正常检测，原因未知。

可用功能：

1. 头显显示。
2. 头显3自由度追踪。
3. 头部6自由度追踪。（配合Nolo套件）
4. nolo手柄按键，触摸板。
5. nolo手柄6自由度追踪。
6. nolo手柄震动。
7. 使用nolo自带手柄建模。
8. nolo手柄双击电源键校准。
9. nolo手柄双击菜单键转身。
10. nolo手柄线速度角速度跟踪。
 
To Do:

无

下载：

https://wwi.lanzouw.com/b0d3w918h
密码:f5vw

食用方法：

~~在[Releases](https://github.com/lixiangwuxian/Viulux-V9-Driver-for-SteamVR/releases)里面下载所需版本的驱动,解压至SteamVr的driver目录下，~~

至蓝奏云下载所需文件，解压至`steamvr/driver`目录下即可。

建议至[Viulux Driver](https://github.com/lixiangwuxian/Viulux-Driver)下载源码自行编译，具体安装及显示配置可以参考Relativty的安装配置部分。

//待补全

又及：官方只能当视频播放器的辣鸡驱动Viulux Clan的[下载地址](https://wwi.lanzouw.com/ieijMy1d1hg)
