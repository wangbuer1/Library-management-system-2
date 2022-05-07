# 基于SSM 的图书馆管理系统

关注公众号： **程序员王不二**，回复 “图书馆3 ” ，即可免费获取完整版的项目代码。此公众号持续分享各种免费java项目源码。

![公众号二维码](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220506172129.jpg)

## 1、项目介绍

基于SSM 的图书馆管理系统拥有两个角色，分别为管理员和学生。具体功能如下：

**管理员**：查看、添加图书，查看添加学生，借还管理，修改密码等

**学生**：查加检索图书、查看个人信息、查看个人借阅情况、修改密码

## 2、项目技术

后端框架：SSM（Spring、SpringMVC、Mybatis）

前端框架：bootstrap、jsp

其它：mysql5-8、tomcat8-10、JDK1.8+

## 3、开发工具

eclipse、idea、myEclipse

## 4、功能介绍

### 4.1 登录

![image-20220507165945027](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220507165947.png)

管理员和学生读者均可以通过此页面的登录系统，登录模块会自动检测签前端是否完整填写账号和密码，再经过后台数据库查询校验并通过后，会分别登录至不同的操作端。

### 4.2管理员-学生管理

![管理员-读者管理](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220507170252.png)

管理员学生管理模块可以对学生进行查看、编辑、删除等功能。

### 4.3管理员-图书管理

![管理员-图书管理](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220507170439.png)

![图书详细信息](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220507170634.png)

管理员-图书管理模块中，管理员可以对图书进行增加、编辑、删除和详情查看等功能，还可以通过图书名字搜索图书，详情可以观看下方视频。管理员读者日志模块同上。

### 4.4用户学生-图书借阅

![用户学生-图书借阅](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220507170615.png)

学生图书查看模块中，可以根据图书名搜索图书，并能查看图书详情和借阅图书。

### 4.5学生个人借还日志

![学生个人借还日志](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220507170643.png)

学生可以通过我的借还日志功能模块查看自己借阅记录。

### 4.6 ER图

![ER图](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220507180351.png)

## 5、视频演示

[点击播放视频，视频位于文章最后](https://mp.weixin.qq.com/s?__biz=MzkwMjM1MjM0Ng==&mid=2247483835&idx=1&sn=89c6f3da46f180e1167c9f1817a154de&chksm=c0a79d0ef7d01418f423b2f41cbc6c75f6c6ff2ea475c7f3727c7bc5db9a9fb0888fb43cb9b3#rd)

## 6、其它项目

[点击访问各种项目源码](https://mp.weixin.qq.com/s?__biz=MzkwMjM1MjM0Ng==&mid=2247483834&idx=1&sn=40517cecf36ce5d7663ed774a033fa2c&chksm=c0a79d0ff7d0141943c5d8da40b489e8ecdda5c345568776f475576506c76a954bd8238dc4f5#rd)





