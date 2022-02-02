# Viulux-V9-Driver-for-SteamVR
将[Relativty](https://github.com/relativty/Relativty)驱动和[OpenHMD](https://github.com/OpenHMD/OpenHMD)缝合而成的Steam VR驱动。

**我不保证此驱动一定能正常使用，也不会对使用此驱动所造成的任何后果负责，使用者应自己承担责任。**

~~可配合Relaivty的摄像头全身追踪。~~ 0.1.2版本之后移除了Relativty的人体识别部分代码，实现位置追踪只能使用Nolo套件

水平有限，Bug在所难免。

如果你没有Nolo套件，请下载v0.1.2版本。后续版本无法正常使用。

bug:

1. 前一次启动SteamVR时VR视图未关，再次启动时头显屏幕只会显示一片红色，重启SteamVR即可。


可用功能：

1. 头显显示。
2. 头显3自由度追踪。
3. 头部6自由度追踪。（配合Nolo套件）
4. nolo手柄按键，触摸板。
5. nolo手柄6自由度追踪。
6. nolo手柄震动。
7. 使用nolo自带手柄建模。
8. nolo手柄双击电源键校准。
 
To Do:

1. nolo手柄双击菜单键转身。<--施工中

食用方法：

在[Releases](https://github.com/lixiangwuxian/Viulux-V9-Driver-for-SteamVR/releases)里面下载所需版本的驱动,解压至SteamVr的driver目录下，
具体显示可以参考Relativity的显示配置部分。

//待补全

又及：官方只能当视频播放器的辣鸡驱动Viulux Clan的[下载地址](https://wwi.lanzouw.com/ieijMy1d1hg)
