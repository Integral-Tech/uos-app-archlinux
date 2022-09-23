# 在 Arch Linux 及其衍生发行版上运行统信 UOS 软件
## 包名与软件名的对应关系
- boardmix-uos -> Boardmix
- yuntucad-uos -> 云图三维
- kdocs-uos -> 金山文档
- rishiqing-uos -> 日事清
- pixso-uos -> Pixso
- mastergo-uos -> MasterGo
- codemao-wood-uos -> 海龟编辑器
- codemao-kitten3-uos -> 源码编辑器
- bcm-convertor-uos -> 编程猫格式工厂
- maxhub-share-uos -> MAXHUB 传屏助手
## 安装
### 从 AUR 安装
可用 paru（推荐）或 yay 安装：
#### paru
```
paru -S boardmix-uos
paru -S yuntucad-uos
paru -S kdocs-uos
paru -S rishiqing-uos
paru -S pixso-uos
paru -S mastergo-uos
paru -S codemao-wood-uos
paru -S codemao-kitten3-uos
paru -S bcm-convertor-uos
paru -S maxhub-share-uos
```
#### yay
```
yay -S boardmix-uos
yay -S yuntucad-uos
yay -S kdocs-uos
yay -S rishiqing-uos
yay -S pixso-uos
yay -S mastergo-uos
yay -S codemao-wood-uos
yay -S codemao-kitten3-uos
yay -S bcm-convertor-uos
yay -S maxhub-share-uos
```
### 用安装包安装
在 Release 页面下载对应软件的安装包（后缀为```.tar.zst```），然后请使用```sha256sum```命令核对 sha256 是否一致。

执行下面命令安装：
```
sudo pacman -U #安装包路径
```

## 卸载
执行下面命令卸载：
```
sudo pacman -Rscnu boardmix-uos
sudo pacman -Rscnu yuntucad-uos
sudo pacman -Rscnu kdocs-uos
sudo pacman -Rscnu rishiqing-uos
sudo pacman -Rscnu pixso-uos
sudo pacman -Rscnu mastergo-uos
sudo pacman -Rscnu codemao-wood-uos
sudo pacman -Rscnu codemao-kitten3-uos
sudo pacman -Rscnu bcm-convertor-uos
sudo pacman -Rscnu maxhub-share-uos
```
