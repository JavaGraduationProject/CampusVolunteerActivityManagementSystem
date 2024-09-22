# 全目录

[更多系统、论文，供君选择 ~~>](https://www.yuque.com/wisebit/blog)


# 83.CampusVolunteerActivityManagementSystem

<p>群: 983063232(入群获取sql文件)</p>
<p>QQ: 206157502(加好友获取sql文件)</p>

<p><h1 align="center">83.校园志愿者活动管理系统</h1></p>


<p align="center">
	<img src="https://img.shields.io/badge/jdk-1.8-orange.svg"/>
    <img src="https://img.shields.io/badge/springboot-5.x-lightgrey.svg"/>
    <img src="https://img.shields.io/badge/vue-3.x-blue.svg"/>
    <img src="https://img.shields.io/badge/小程序-3.x-yellow.svg"/>
</p>

# 简介

> 本代码来源于网络,仅供学习参考使用,请入群(983063232)后联系群主索要sql文件!
>
> 提供1.远程部署/2.修改代码/3.设计文档指导/4.框架代码讲解等服务
>
> 后台管理地址: http://localhost:8081/#/login
>
> 用户名: 202160501 密码: 123456


# 环境

- <b>IntelliJ IDEA 2009.3</b>

- <b>Mysql 5.7.26</b>

- <b>Tomcat 7.0.73</b>

- <b>JDK 1.8</b>

- <b>maven 3.2.5 </b>

- <b>redis </b>




## 缩略图

![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/90078c73-093f-4b1f-9a9a-15985ba17327.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/1e56f761-5bbc-4fe6-be46-de920eac9221.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/debec934-307f-448c-9719-ce28d9bf1f88.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/6b1ca971-64ab-4dbb-a553-f9a991622573.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/bc35c6c2-091d-423c-be96-c73f50cdd254.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/a10c05ac-c173-4f7b-958f-ad54a48811ae.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/df26e04b-68ac-400d-a8ff-edf07787219a.png)








#### 【大学生志愿者小程序】

|  小程序模块    |  文件路径    |
| ---- | ---- |
|  小程序后端    |   /backend   |
|  小程序前端    |  /frontend    |
|  web前端    |  /vol-web    |

项目包含有完整的志愿者在小程序端报名活动，管理员在web端审核通过活动，志愿者通过二维码扫码报名签到的功能。图片建议放在   /home/cov/images/  路径下，

二维码图片路径是/home/cov/images/qrcode/，

这样通过  http://{公网IP}:8888/images/ xxx.jpg 就可以访问到图片



#### 【涉及技术】

前端    iview + vue + vuex + axios

后端    springBoot + redis + Mysql



#### 【附件】

|  小程序文件模块    |  文件路径    |
| ---- | ---- |
| 1、数据库设计表     |  /志愿者数据库设计v1.0.doc    |
| 2、小程序Rest接口详细说明 | /志愿者小程序后端接口说明.md   |
|  3、小程序开发文档---开发环境规约和说明    | /志愿者小程序开发文档.docx     |
| 4、数据库脚本 | /covdb.sql |



#### 【参考文档】

ivew  http://v1.iviewui.com/docs/guide/install

小程序  https://developers.weixin.qq.com/miniprogram/dev/framework/



#### 【使用方法】

##### 1、启动后端

##### 【安装后端环境】

后端需要java8，mysql,redis 环境，使用maven管理后端项目



##### 【启动后端项目】

用idea打开backend，maven加载好后，启动项目，后端占用8888端口；


##### 2、启动前端

##### 【启动web后台】

web端进入vol-web，使用如下指令启动前端

需要node.js

```bash
npm install
npm run serve 
```

##### 【启动小程序前端】

将frontend文件夹导入微信小程序开发者工具


