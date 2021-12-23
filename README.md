# 文档记录图床搭建

经常用markdown文档记录，图片的链接往往是本地，发生上传的操作时图片往往丢失，搭建个人图床帮助更好记录。

## 准备工作

**PicGo+Github+Typora**

Gitlab 用于仓库管理系统的开源项目，使用Git作为代码管理工具，并在此基础上搭建起来的Web服务。在这里我们先把它当做图片存储的服务器免费快速。

PicGo: 一个用于快速上传图片并获取图片 URL 链接的工具

Typora将给你作为一个读者和作家的无缝体验。它删除了预览窗口、模式切换程序、标记源代码的语法符号以及所有其他不必要的干扰。将它们替换为真正的实时预览功能，以帮助您专注于内容本身。

### Pic-Go

PicGo 官网

https://picgo.github.io/PicGo-Doc/

![image-20211224004747877](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240047927.png)

下载地址

https://github.com/Molunerfinn/PicGo/releases

### Github

新建github仓库

![image-20211224004357624](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240043662.png)

例如：https://github.com/ID-Wangqiang/MyBlogImg

获取github用户token

![image-20211224003926912](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240039957.png)

![image-20211224004117745](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240041792.png)

保存这个生成的token，只生成一次

![image-20211224004211861](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240042908.png)

配置Pic-go客户端

![image-20211224004242103](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240042152.png)

![image-20211224004514690](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240045735.png)

上传图片pic-go客户端测试

![image-20211224004444313](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240044361.png)

### Typora

配置typora上传图片设置

![image-20211222202109168](https://git.youle.game/wangqiang01/img/-/raw/master/pictures/2021/12/22_20_21_9_image-20211222202109168.png)

大功告成

![image-20211224004613575](https://cdn.jsdelivr.net/gh/ID-Wangqiang/MyBlogImg/img/202112240046621.png)