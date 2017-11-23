# ASUS_FX53VD_10.13.1EFI (Kext驱动被破坏,无法正常驱动了,请参见下方的10.12.6)
## EFI & HotPatch Author:QiuChenly
### 机器类型：笔记本 i7 7700HQ
### 机器显卡：GTX1050 4GB + Intel HD 630 2GB
### 机器声卡：ALC235
### 机器网卡：8188L驱动有线网卡，无线网卡无解。
## 本EFI工作的硬件：
### 1.驱动原生HD630显卡驱动。
### 2.驱动有线网卡。
### 3.驱动键盘，USB HD WebCam.
### 4.亮度可调节，自动保存亮度配置。
### 5.声音使用AppleALC 235 Patch 成功，内置mIC无声，耳机孔背景音。
### 6.ACPI电池驱动OK。
## 本EFI待完善的硬件：
### 1.睡眠无法唤醒。
### 2.USB3.0无法使用。
### 3.TouchPad 为ELAN1200，I2C通道，暂时无法驱动。
### 4.键盘键位映射有问题。
### 5.关机自动重启。
# ASUS_FX53VD_GL553VD_ 10.12.6 几乎完美efi
## EFI & HotPatch Author:QiuChenly
## 本次更新修正了部分历史遗留问题.
## 如果发现部分硬件本应该工作却没有工作,请至华硕官网下载303版本BIOS固件进行BIOS更新.
## 华硕FX53VD 飞行堡垒个人交流群:
### ![alt tag](https://raw.github.com/QiuChenly/ASUS_FX53VD_10.13.1EFI/master/macOS10.12_98%25%E5%AE%8C%E7%BE%8Eefi/QQ.jpg)

## 使用前提:请到sle下将以下几个文件改名:
### ![alt tag](https://raw.github.com/QiuChenly/ASUS_FX53VD_10.13.1EFI/master/macOS10.12_98%25%E5%AE%8C%E7%BE%8Eefi/tips.jpg)

## 工作的硬件:
### 显卡原生驱动HD630
### 声卡自编译ALCHDA,耳机功放完美,耳机麦克输入可用,外放完美,内置MIC无效.
### 触摸板可以驱动,i2c就可以,不过elan1200驱动会被识别为画板,所以等待大神驱动完善了再行解决.
### 键盘 USB 全部内建,USB3.0 口5GB/s正常.
### 电源显示完美.
### 睡眠唤醒完美.
### 蓝牙二合一卡无解,已更换为淘宝NGFF  AR9565二合一卡驱动成功,信号很差,不建议购买,建议购买拆机NGFF卡免驱顺心.
### 亮度可调节,自动保存亮度配置.
## 待完善的Hardware:
### 1.关机有几率因为USB问题无法关机.
### 2.键盘等无法调节.DSDT正在研究中.
### 3.请勿在10.13.x系统上使用本EFI.未经测试.因为已从10.13回退到10.12.6.

# 经过测试发现上传到Git的kext驱动会被强制修改文件信息,所有KEXT文件将会失效,故已重新压缩为zip上传.
