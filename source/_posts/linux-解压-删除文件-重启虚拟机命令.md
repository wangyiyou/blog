---
title: linux-解压/删除文件-重启虚拟机命令
date: 2021-02-23 21:11:21
tags: linux 
---

# 解压指令
---
## 对于 tar.xz 解压

```
xz -d file.tar.xz

tra -xvf file.tar
```
---
##  .tar 结尾

```
tar -xvf filename
```
---
## .gz 结尾
```
gzip -d filename
```
---

>  五个独立命令只能使用一个
> -c 建立压缩档案
> -x 解压
> -t 查看内容
> -r 向压缩归档文件末尾追加文件
> -u 更新原压缩包中的文件

> -z:有gzip属性
> -j:有bz2属性
> -v:显示所有过程
> -Z:有compress属性的
> -O:将文件揭开到标准输出

---
# 删除文件

```
rm -ivrf file
```
---


# 重启虚拟机

```
reboot
```

---


# 关闭虚拟机

```
poweroff
```
---