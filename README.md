## Machenike-F117-B6-Hackintosh-OC 黑苹果OC 配置

[我的博客同步更新](https://www.chenweikang.top/?p=713 "左手代码右手诗")

### 更新记录

-  release-20210220-0.6.6(mod)

更新到opencore 0.6.6-mod-release;

更新相关驱动，默认为1820a网卡配置，免驱卡请自行移出config里的1820a相关配置(mod版本使用occ修改配置时请切换到mod版本模式);

支持 big sur mac 11.1;


-  release-20200809-0.6

更新到opencore 0.6.0 release;

更新相关驱动，新增1820a网卡配置;

mac 11.0 暂未测试,有条件可自行尝试;

### 主机配置
- CPU：I7-8750H
- 屏幕：京东方 1080P/144hz
- 内存：32GB 挚科DDR4 2666 X 2
- WFFI/蓝牙：BCM94360CS2( 拆机卡 ) 免驱/dw1820a
- 硬盘：PM981 m.2(256G)装win / 光威 m.2(512G)装mac


### BOIS设置
```
无需设置
```

### 安装和问题参考

- 默认config.plist不带1820a驱动,1820a使用config_1820a.plist！

- 设置开机默认启动Mac：1.引导界面直接ctrl+enter进入 / 2.偏好设置->启动磁盘 设置默认启动盘。
 
- 镜像下载：[黑果小兵博客镜像地址](https://mirrors.dtops.cc/iso/MacOS/daliansky_macos/ "黑果小兵镜像")

- 常见问题：[安装常见问题](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html "安装常见问题")

- Etcher烧录工具：[Etcher烧录工具](https://www.balena.io/etcher/ "Etcher烧录工具")

- OCC：[OC配置可视化编辑工具](https://mackie100projects.altervista.org/download-opencore-configurator/ "OCC")

- OpenCore For Mod[OpenCore mod版本发布](http://bbs.pcbeta.com/viewthread-1838814-1-1.html "OpenCore For Mod")

### 已知bug

偶尔冷启动声卡无法驱动，重启即可


