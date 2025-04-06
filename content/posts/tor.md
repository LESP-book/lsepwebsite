---
title: "如何使用洋葱浏览器"
draft: false
date: 2025-03-30
---

# Tor浏览器使用教程

为了防止中修政府的网络管控，我们推荐使用Tor（洋葱）浏览器访问论坛。

Tor浏览器的简易使用教程如下。

一、下载Tor浏览器

Tor浏览器的中文官方网址：[https://www.torproject.org/zh-CN/](https://www.torproject.org/zh-CN/)

**为确保安全，不要使用第三方网站上的Tor浏览器安装包**

二、安装Tor浏览器。（仅展示Windows操作系统）

1.双击运行安装程序

2.选择语言，点击OK

![image.png](https://image.us-lax-1.linodeobjects.com/tor/image.png)

3.选择安装位置，点击“安装”

**Tor浏览器是一款便携的软件，你可以直接将其安装到你的U盘中，方便携带，在U盘中使用该浏览器，也不易在电脑中留下使用痕迹**

![image1.png](https://image.us-lax-1.linodeobjects.com/tor/image1.png)

4.安装完成，将看到安装目录下的Tor Browser文件夹

![image2.png](https://image.us-lax-1.linodeobjects.com/tor/image2.png)

三、使用VPN连接外网

**Tor浏览器必须使用外网连接，在中国境内直接连接难度大且危险**

**注意，必须使用VPN的全局模式进行连接**

![image3.png](https://image.us-lax-1.linodeobjects.com/tor/image3.png)

连接完成后，可以使用IP测试网站，测试自己的IP是否已经处于境外

IP测试网站例如：[https://whatismyipaddress.com/](https://whatismyipaddress.com/)

四、启动Tor浏览器并连接

1.双击Tor Browser文件夹中的Tor Browser快捷方式，启动Tor浏览器

2.确保你已经使用全局模式的VPN连接上了外网，然后点击Tor浏览器中的“连接”

![image4.png](https://image.us-lax-1.linodeobjects.com/tor/image4.png)

3.等待进度条

![image5.png](https://image.us-lax-1.linodeobjects.com/tor/image5.png)

4.当你看到如下页面时，说明Tor网络连接成功，你也可以使用IP测试网站，测试自己的IP是否与自己的实际地址和VPN节点地址都不同

![image6.png](https://image.us-lax-1.linodeobjects.com/tor/image6.png)

接下来，你可以在Tor浏览器中输入网址，开始访问论坛了

五、一些问题

有一些VPN客户端（例如Clash、V2Ray）无法直接连接Tor网络，需要配置连接

![image7.png](https://image.us-lax-1.linodeobjects.com/tor/image7.png)

重启浏览器，点击配置连接……

![image8.png](https://image.us-lax-1.linodeobjects.com/tor/image8.png)

在左侧的“连接”中，将页面划到底端，进入进阶中的“设置”

![image9.png](https://image.us-lax-1.linodeobjects.com/tor/image9.png)

在以下的连接设置中，勾选“我通过代理连接互联网”，代理类型选择SOCKS5，地址填写127.0.0.1，端口填写你的VPN的端口号，设置完成后点击“确定”

![image10.png](https://image.us-lax-1.linodeobjects.com/tor/image10.png)

Ps：以Clash为例，你可以在“常规（General）”选项中查询端口号（Port）

![image11.png](https://image.us-lax-1.linodeobjects.com/tor/image11.png)

设置完成后，再次点击Tor浏览器首页的“连接”即可成功连接Tor网络
