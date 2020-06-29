# [科学上网]

> 此项目提供用于paldier带软件中心固件路由器的科学上网。

---

**提示1：** 如果提示检测到离线安装包名有非法关键词，开启路由器的SSH功能，登录并输入以下命令后，再进行离线安装。(需要请将软件中心更新到最新版)
```bash
sed -i 's/\tdetect_package/\t# detect_package/g' /jffs/softcenter/scripts/ks_tar_install.sh
```

---

## 机型/固件支持（文字版）

### [mips](https://github.com/zusterben/plan_a/tree/master/bin/mips)

> **mips**离线安装包仅能在mips架构机器上使用！具体支持机型如下：

* 华硕系列：`BLUECAVE`
* 斐讯系列：`K3C`

#### 注意：

* 目前此系列必须挂载U盘才能开启软件中心，同时因为驱动bug的原因无法支持fat格式，优先推荐ext格式，且推荐读写速度高的U盘
* 强烈建议使用chrome或者chrouium内核的或者firefox浏览器！以保证最佳兼容性！

----

### [arm](https://github.com/zusterben/plan_a/tree/master/bin/arm)

> **arm**离线安装包仅能在博通平台，且linux内核为2.6.36.4的armv7架构的机器上使用！

**arm**支持机型如下：

* 华硕系列：`RT-AC68U` `RT-AC66U-B1` `RT-AC1900P` `RT-AC87U` `RT-AC88U` `RT-AC3100` `RT-AC3200` `RT-AC5300`
* 斐讯系列：`K3`
* 网件系列：`R6900P` `R7000P` `R7000`
* 领势系列：`EA6700`
* ARRIS系列：`SBRAC1900P` `SBRAC3200P`
* 其他：`XWR3100` `XWR3150`

#### 注意：

* 强烈建议使用chrome或者chrouium内核的或者firefox浏览器！以保证最佳兼容性！

----

### [arm64](https://github.com/zusterben/plan_a/tree/master/bin/arm64)

> **arm64**离线安装包支持所有arm64/aarch64架构的机器上使用！

**arm64**支持机型如下：

* 华硕系列：`RT-AC86U` `GT-AC2900` `GT-AC5300` `RT-AX88U` `RT-AX86U` `RT-AX68U` `RT-AX89X`
* 网件系列：`R7900P` `R7960P` `R8000P` `RAX80`


#### 注意：

* 目前此系列必须挂载U盘才能开启软件中心，同时因为驱动bug的原因无法支持fat格式，优先推荐ext格式，且推荐读写速度高的U盘
* 强烈建议使用chrome或者chrouium内核的或者firefox浏览器！以保证最佳兼容性！

----

### [armng](https://github.com/zusterben/plan_a/tree/master/bin/armng)

> **armng**离线安装包能在内核为4.1和3.14的armv7架构的机器上使用！

**armng**支持机型如下：

* 华硕系列：`RT-AX56U` `RT-AX58U` `TUF-AX3000` `RT-AX82U` `RT-ACRH17` `RT-AC2200`
* 网件系列：`RAX20` `RAX50`

#### 注意：

* 目前此系列必须挂载U盘才能开启软件中心，同时因为驱动bug的原因无法支持fat格式，优先推荐ext格式，且推荐读写速度高的U盘
* 强烈建议使用chrome或者chrouium内核的或者firefox浏览器！以保证最佳兼容性！

----

### [mipsel](https://github.com/zusterben/plan_a/tree/master/bin/mipsel)

> **mipsel**离线安装包仅能在mipsel架构的机器上使用！

**mipsel**支持机型：

* 华硕系列：`RT-AC85U` `RT-AC85P`

#### 注意：

* 目前此系列必须挂载U盘才能开启软件中心，同时因为驱动bug的原因无法支持fat格式，优先推荐ext格式，且推荐读写速度高的U盘
* 强烈建议使用chrome或者chrouium内核的或者firefox浏览器！以保证最佳兼容性！

