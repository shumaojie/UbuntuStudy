#UbuntuStudy#
##安装裸包到树莓派3生产环境##
1. 下载安装包16.04（1.1GB） 
https://ubuntu-mate.org/raspberry-pi/ubuntu-mate-16.04-desktop-armhf-raspberry-pi.img.xz
2. 利用解压缩软件解压缩ubuntu-mate-16.04-desktop-armhf-raspberry-pi.img （7864.320K）
3. 在windows系统下利用Win32DiskImager刻录到TF卡中
4. 刻录完以后在windows系统下显示为63.9M，空闲44.0MB
5. 树莓派没上电下把tf卡插入到tf卡槽上电
6. 系统配置
7. 选择语言，键盘模式，用户名，选择自动登录(重点)，大概10分钟后会自动重启
8. 主题包的配置。首n选项->外观->MATE Tweak. 在界面中面板选择Cuprtino
9. 重启系统，才能进行网络配置。在右上角出现的无线符号选择相对应的无线网。
10. 在命令行中执行sudo apt-get update 
11. 在命令行中执行sudo apt-get upgrade  （需要花费较长时间）
12. 重启系统
13. 安装raspi-config 进行配置。sudo apt-get install raspi-config
14. 进行扩容
15. 配置远程登录功能  sudo apt-get install xrdp
14. 安装sudo apt-get install git
15. 安装means配置。
16. 把无线当作热点进行配置。






##常用指令##
1. sudo  apt-get  update:更新软件安装源
2. sudo  apt-get  upgrade:系统升级
3. 查看文本 pluma ***.config
4. 键盘打开命令行  ctr+alt+t





##常见软件##
1. lamp安装
2. python开发环境
3. opencv 安装
4. Ftp的安装
5. git的安装




##FAQ##



