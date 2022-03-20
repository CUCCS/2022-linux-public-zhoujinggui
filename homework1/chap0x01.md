# 第一章：（实验）

# 实验问题

#### 一、 调查并记录实验环境的如下信息：
  - 当前 Linux 发行版基本信息

![查询-Linux发行版本](.\picture\查询-Linux发行版本.jpg)

  - 当前 Linux 内核版本信息

![查询-Linux内核版本](.\picture\查询-Linux内核版本.jpg)

###### 阿里云云上liunx

![查询-云上版本](.\picture\查询-云上版本.jpg)



#### 二、 Virtualbox 安装完 Ubuntu 之后新添加的网卡如何实现系统开机自动启用和自动获取 IP？



#### 三、 如何使用 `scp` 在「虚拟机和宿主机之间」、「本机和远程 Linux 系统之间」传输文件？



#### 四、 如何配置 SSH 免密登录？

先在Ubuntu中安装`ssh`软件

```c++
//输入
sudo apt-get install ssh
```

![下载ssh](.\picture\下载ssh.jpg)

安装完成后进行加密设置

```c++
//输入
ssh-keygen -t rsa //ras为加密算法，还可以使用des算法
```

![加密设置](.\picture\加密设置.jpg)

