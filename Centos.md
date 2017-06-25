
## ls 命令

ls -lh /dir

-h 表示显示文件大小人性化显示

## 创建目录

mkdir test

mkdir -p a/c

递归创建目录

## 切换目录
change dir

cd ~ = cd 
# rmdir 删除空目录

# rm -rf 【文件】 不区分文件和文件夹
强制删除 f
rm -rf / 【强制递归删除】
## tab 目录补全

## 命令补全

## 复制目录
cp -r dir1 dir2
-r 表示复制目录
## 剪切和改名
mv 

## locate 搜索
updatebd
/var/lib/mlocate
/etc/locate.cnf
## 搜索命令的命令 
whereis pwd 命令所在位置和帮助文档
which pwd 命令位置
##
echo $PATH 打印变量
## find 
find 【搜索范围】 搜索选项
find / -name cc
## man 帮助
man ls
显示文档 


## centos 常用命令

http://www.cnblogs.com/vamei/archive/2013/03/03/2871198.html

## 文件夹复制 cp
cp -r dir1 dir2

## 添加sudo 用户

https://www.digitalocean.com/community/tutorials/how-to-create-a-sudo-user-on-centos-quickstart

## 安装 Java
参考 http://www.jianshu.com/p/848b06dd19aa

```sh
wget http://download.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x64.rpm?AuthParam=1497444126_88bb9a2961f93df028f76d2925ab61f5
```

http://www.cnblogs.com/always-online/p/4691507.html 配置Java

## 安装tomcat服务

https://www.digitalocean.com/community/tutorials/how-to-install-apache-tomcat-8-on-centos-7

## 如何实现一个操作系统
https://www.zhihu.com/question/22463820
