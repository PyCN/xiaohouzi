# LINUX-客户端Clash

Clash linux 版本0.19.18

支持ubuntu centos 桌面图形版 X86处理器

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/asd.jpg)

### 第1步： 下载安装Linux版本的Clash

首先下载Linux版本的clash客户端，github下载链接。

[https://github.com/Fndroid/clash\_for\_windows\_pkg/releases](https://github.com/Fndroid/clash\_for\_windows\_pkg/releases)

下图所示[Clash.for.Windows-0.19.18-x64-linux.tar.gz](https://github.com/Fndroid/clash\_for\_windows\_pkg/releases/download/0.19.18/Clash.for.Windows-0.19.18-x64-linux.tar.gz) 为x86 一般intel amd X64 处理器

如果您是使用ARM 内核cpu 请您对应下载 arm 版本的

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/QQ%E5%9B%BE%E7%89%8720220514220224-1024x573.png)

本站CLASH FOR LINUX 下载地址

[CLASH LINUX 下载](https://www.shenlejiang.xyz/upload/xiaohouzi2/Clash.for.Windows-0.19.18-x64-linux.tar.gz)

—->>>>加速下载链接地址—crhome谷歌浏览器请手动复制一下链接到新页面下载

[http://download.xiaohouzi.club:276/upload/xiaohouzi2/Clash.for.Windows-0.19.18-x64-linux.tar.gz](http://download.xiaohouzi.club:276/upload/xiaohouzi2/Clash.for.Windows-0.19.18-x64-linux.tar.gz)

### **第二步** 解压安装

切换到您的clash下载目录

将下载的linux版本的clash压缩文件解压，解压命令如下：

```
tar -zxvf Clash.for.Windows-0.19.16-x64-linux.tar.gz
```

解压后切换到 clash 目录 并给与cfw文件权限

```
cd Clash.for.Windows-0.19.16-x64-linux
```

```
chmod +x cfw
```

运行clash

在clash文件目录下 输入命令./cfw 运行clash

```
./cfw
```

clash linux界面

clash linux界面

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/1652241366-null\_2022-05-11\_11-55-48-1024x574.png)

### 第三步导入订阅

进入小猴子2.0页面—>

[小猴子订阅中心](https://www.xiaohouzi.store/)

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/QQ%E5%9B%BE%E7%89%8720220514222313-1024x728.png)

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/QQ%E5%9B%BE%E7%89%8720220514221756-1024x477.png)

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/QQ%E5%9B%BE%E7%89%8720220514222517-1024x734.png)

再点击clash左侧的proxies（代理），在第一个里面选择自己想要使用的节点，我这里选择香港为例说明

### 第四步：手动设定Linux系统代理IP和端口

因为linux的系统分支不同，有的可能是权限的问题，clash无法在linux 自动设定代理端口，需要手动设定，设定的方法如下：

我们在clash 可以看到 端口那里显示clash代理端口为7890

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/QQ%E5%9B%BE%E7%89%8720220514222926-1024x715.png)

在linux 系统设定代理端口

已ubuntu为例

打开linux的设定—>网络 ，点击代理后面的设定，安装下图设定http https socks 的ip设置为127.0.0.1（本地网络代理ip），端口为 7890（clash代理端口）

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/1652242889-null\_2022-05-11\_12-20-24-1024x561.png)

现在已经完成了，我们打开浏览器试试是否成功！！

![](https://www.shenlejiang.xyz/wp-content/uploads/2022/05/1652243019-null\_2022-05-11\_12-23-13-1024x594.png)

