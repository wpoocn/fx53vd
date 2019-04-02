# ASUS_FX86FE_GL553VD_ 10.14.x
### `Support Device: FX86FE(I7-8750H)`
- 
- (所有开源驱动非本人制作，我只是将这些驱动结合在一起打造一台基本完美的黑苹果工作站。感谢国外各个开源项目。)
##  EFI & HotPatch Author:QiuChenly
>  **如果发现部分硬件本应该工作却没有工作,请至华硕官网下载303版本BIOS固件进行BIOS更新.** 
>> **华硕FX86FE 飞行堡垒个人交流群:** 
>>> ![alt tag](https://raw.github.com/QiuChenly/ASUS_FX53VD_10.13.1EFI/master/macOS10.12_98%25%E5%AE%8C%E7%BE%8Eefi/QQ.jpg)
# 最新 EFI V1
(最新 - 2019.3.20日更新，更新已转移到中科大服务器.)

# 1.0 更新：
# [Download](EFI_FX86FE - V1.zip)
发布于 2019 年 3 月 20 日

#### EFI - V1 功能性更新包含对驱动的更新。

##### DSDT
```
1. 解决了睡眠唤醒,声卡网卡等必要的SSDT补丁.
```
##### 驱动程序
```
1. 更新了部分Kext到新版本.
```
##### Clover EFI
```
1. 更新到4900+,支持10.14.4启动而不会造成禁行问题.
```
#### 安装 EFI - 1 更新会将：
```
1. 上方提到的各种驱动和DSDT更新到最新.
```
#### 要安装你 Hacintosh 上的“EFI V1”版本补丁，请进行以下操作：
1. 使用Clover挂载你的EFI分区.
2. 将你的SMBIOS信息或整个EFI目录保存至其他地方备份.
3. 将下载的EFI_FX86FE - V1.zip文件解压至根目录,保证文件夹名为"EFI".
4. 将你的SMBIOS数据还原到EFI的config文件中,主要是序列号和三码.如果你不知道什么是SMBIOS数据还原/备份,请无视这句话或手动随机生成一个机器数据.
5. 重启.
