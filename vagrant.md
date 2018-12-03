# Project: vagrant
 ## vagrant 基础知识
- 总结下作用:   
 1. 可以统一环境配置
 2. 方便快速构建虚拟机集群环境
 3. 小团队分发配置环境  

- 与docker对比:   
都是基础工具，定位还是不太一样，docker应用环境配置部署等。  
vagrant基本上市管理虚拟机。  

 ## vagrant 构建虚机
1. 安装virtualbox
2. 给vagrant新增一个box(添加虚机镜像)

```
vagrant box add centos/7
```

centos/7表示box的名称，如果当前路径没有，vagrant就会到官网的Vagrant Cloud中寻找并下载。

国内速度下载速度如果没有搭梯子一般会很慢，这里提供了一个下载链接： 
https://pan.baidu.com/s/1DIis9g8JoyXMJvkkWkiL8A 
这种将本地的box添加到Vagrant的命令如下：

```
vagrant box add -name 'centos/7' [box放置的位置]
```

下载后的镜像位置:  
```
Mac OS X and Linux: ~/.vagrant.d/boxes
Windows: C:/Users/USERNAME/.vagrant.d/boxes
```

3. 创建vagrant工作目录
```
cd vagrant_workspace
mkdir docker01
cd docker01
``` 
注意:本地vagrant工作目录所有内容会被拷贝到生成的虚机环境中，对应/vagrant目录。

4. 初始化虚机环境即自动生成vagrantfile配置文件  
```
vagrant init centos/7
```
注意: 如果有vagrantfile模板，可以自己写，不用执行该步骤  

5. 启动虚机环境
```
vagrant up
```

1. shell语言
2. awk,sed 掌握
3. vim查找替换

 ## todo: vagrant 创建集群

# resource
- [Vagrant介绍-从使用到放弃再到掌握完全指南- 我在一年内使用Vagrant的心路历程](https://jimmysong.io/posts/vagrant-intro/)  
`虽然只是介绍了vagrant的结构，但是其`[使用vagrant构建k8s/istio分布式环境](https://github.com/rootsongjc/kubernetes-vagrant-centos-cluster)`还是相当实用,以及`[vagrant multi machine](https://www.vagrantup.com/docs/multi-machine/)` `
- [使用Vagrant和Virtual Box创建一台CentOS7虚拟机](https://blog.csdn.net/wang465745776/article/details/80720523) 
- [用Vagrant和Ansible搭建持续交付平台](https://www.linuxidc.com/Linux/2018-04/151775.htm)  
- [Vagrant系列：Vagrant基本使用入门](https://www.linuxidc.com/Linux/2018-04/151772.htm)  
- [vagrant learning](https://github.com/whorusq/vagrant-learning) 
- [vagrant在最小化DevOps中的作用- 拼命三郎OL](https://studygolang.com/articles/16329?fr=sidebar)  
- [拼命三郎ol](https://www.jianshu.com/u/1d7a72cd4230)  
- [第一期|使用docker构建高可用的开发环境](https://segmentfault.com/l/1500000011347031)  
- [预备课：深入理解 Docker 内部原理及网络配置](https://segmentfault.com/l/1500000011347031)  
