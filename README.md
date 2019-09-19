# 「Dasyatis 的 Arch Linux 安装脚本」

### [返回 Dasyatis 主站 >>](https://www.bobby285271.top/)

## 特性
* 极易读懂的脚本。
* 零交互安装。

## 使用
可配合 [本人的 Arch Linux 安装镜像](https://github.com/bobby285271/Archiso) 使用。

获取脚本：
```
# wget https://raw.githubusercontent.com/bobby285271/Archinstaller/master/install.sh
```

### 由于安装过程中几乎零交互，请先仔细阅读脚本内容，必要时对文件进行编辑。

接下来使用管理员权限执行脚本：
```
# bash install.sh
```

## 说明
安装脚本将对以下文件进行**编辑**，意味着这些文件的**本地版本**和 **Arch 打包者提供的版本**将有所不同（按照编辑先后顺序排序）：
```
/etc/pacman.d/mirrorlist
/etc/locale.gen
/etc/locale.conf
/etc/hosts
/etc/hostname
/etc/lightdm/lightdm.conf
/etc/pacman.conf
/etc/environment
/etc/sudoers
```
