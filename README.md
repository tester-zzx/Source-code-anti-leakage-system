### 介绍



对源代码进行加密（支持所有软件开发语言C、C++、C#、Java、Vue、Php、Python等。），加密后只可以在本地打开，离开公司网络（比如说使用U盘拷贝，浏览器外发，QQ、微信外发出去）就打不开。支持常见的开发工具比如说IDEA、vscode等等。


对于外协人员可以只加密公司的项目，不加密个人文件，不影响个人正常使用。


对于出差人员，可以设置离线时间，时间之内加解密正常工作，超过时间后被加密过后的文件无法打开或打开为乱码。
有完整清晰地审批流程供有外发需求的员工使用。

### 软件架构


网盾软件采用C/S架构，即客户端/服务器架构，所有软件均私有化部署。软件包括客户端----服务器---管理端，


服务器端：负责后台连接数据库，对所有的策略及日志都存入后台数据库进行保存，所有管理端及客户端都连接服务器端。


管理端：安装在管理员端负责对客户端电脑进行策略下发，及调取服务器日志进行查询。


客户端：主要是安装员工电脑，对员工电脑记录控制加密。


### 方案


对于开发的源代码，泄密只可能发生在两个位置，一个是个人计算机，一个是版本管理服务器。



 **安装教程** 

    见使用说明

