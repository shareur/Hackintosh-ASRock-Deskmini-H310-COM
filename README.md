# Hackintosh : ASRock Deskmini H310/COM



## 适用系统版本

MacOS 10.15.0 Catalina

## 检查项

- [x] apple store/TV 账号使用完美
- [x] 睡眠完美
- [x] 开关机完美
- [x] 音频自动转换耳机与显示器音响完美
- [x] usb2.0 & 3.0 完美
- [x] DP、HDMI输出2K显示完美（没有4K显示器，没有测试双显示器输出）VGA不支持
- [x] 蓝牙正常 必须接天线信号才好
- [x] 无线正常 必须接天线信号才好
- [x] 有线网络完美

## 主机配置

|                准系统 | ASRock H310/COM BIOS 4.1 |
| --------------------: | ------------------------ |
|                   CPU | I3-8100                  |
|                  显卡 | 集成显卡 UHD 630         |
|                  内存 | DDR4 8G * 2              |
|             网卡&蓝牙 | BCM94360CS2              |
|                  硬盘 | 东芝 240G sata 固态      |
| M.2转接卡&转接线&天线 | 某宝随手淘               |
|                显示器 | BenQ BL2420PT            |

## 使用方法

1. 按照黑果小兵的介绍一步步安装
2. 安装完成，使用别的电脑挂载硬盘efi分区
3. 拷贝替换同名目录下文件即可



## 特别感谢

### [leogitpro](https://github.com/leogitpro)/**[Hackintosh-DeskMini310](https://github.com/leogitpro/Hackintosh-DeskMini310)**

CLOVER目录下基本都用的这位老哥的，可以按照这位老哥的指导去驱动BCM94352Z

在我的设备上发现usb2.0可以识别，usb3.0异常就用了clover configuration软件自带的下载更新了USBinjectall.kext

### [[黑果小兵】macOS Catalina 10.15 19A583 正式版 with Clover 5096原版镜像[双EFI双平台版]](https://blog.daliansky.net/macOS-Catalina-10.15-19A583-Release-version-with-Clover-5093-original-image-Double-EFI-Version.html)

感谢黑果小兵的安装镜像及说明，排除硬件问题后，流畅安装无压力

APPLE，BOOT目录下文件均是黑果小兵的











