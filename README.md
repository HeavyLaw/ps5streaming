# ps5streaming
无采集卡0成本将PS5游戏画面推流到bilibili进行直播（2024年版）

## 项目背景
8月20日，《黑神话：悟空》终于上架，终于在PS5上可以玩到国内自制的3A大作！

本来想试着每天下班后在bilibili上边直播边玩，但是去网上转了一圈发现没有很完备的保姆级的教程，要么是两三年前的，要么解决方案不清晰，自己折腾了一番，终于是实现了无采集卡0成本将PS5游戏画面低延迟、满血画质的推流到bilibili进行直播。话不多说教程开始！

## 适用场景和问题
本教程适合有些许动手能力、理解能力的同学，技术稍微会涉及到网络和容器，但是只要能一步一步跟着教程实施，基本没问题（生命在于折腾）。

可能很多同学搜到了其它教程，然后卡在了其中某一步，如果不想重头再来，不用担心，本教程也可用于解决以下问题（因为每一步都会详细讲解）：

1、有PS5，但是不知道如何科学上网的同学

2、采集卡性能受限或不想使用采集卡，又想低延迟高画质直播的同学

3、B站粉丝低于50，无法获取rtmp推流地址的同学（强烈吐槽这一点，B站也没有明显的提示，找了很久才发现改了直播规则，而且开播流程和界面和之前也差别好大）

4、已经实现推流到twitch上，但是不知道如何劫持域名转发到本地DNS服务器上的同学

## 准备工作
**必需：1台PS5（看本教程肯定得有这个吧），1台PC电脑/笔记本，1台路由器，PC端安装科学上网工具（v2rayNG、clash等）**

### 1、PS5科学上网
具体原理：PS5和PC电脑/笔记本组建局域网，在PS5网络配置代理，转发到PC电脑/笔记本上的clash进行科学上网。

**Step One:**
首先在电脑的clash for windows客户端开启“LAN连接“


### 2、注册Twitch并在PS5上直播

### 3、安装Docker用于部署本地直播服务和DNS服务进行域名劫持和转发重写

## 操作步骤
