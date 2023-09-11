# proot-distro-ubuntu 
## termux和termux:x11下载地址
termux官方下载：https://github.com/termux/termux-app/releases/tag/v0.118.0
termux:x11官方下载：https://github.com/termux/termux-x11/releases/tag/1.03.00
## 系统镜像安装
下载上方文件列表中的 `ubuntu-rootfs.tar.gz`
导入镜像：`proot-distro restore storage/downloads/ubutnu-rootfs.tar.gz`
登录：`proot-distro login --user linux --shared-tmp ubuntu`
启动桌面：`sh startxf.sh`
### 用户密码114514
