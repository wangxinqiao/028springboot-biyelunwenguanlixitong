# 028springboot毕业论文管理系统
028springboot毕业论文管理系统

#### 介绍
```
毕业论文对于高校学生而言是对自己在学校所学的专业知识和技能的总结,对高校的教育而言是对毕业学生最后的一次全面的考核。
在毕业论文完成整个的过程中,需要学生与导师、导师与专业负责人、专业负责人和校方管理人员的密切合作。
但在现实中,某个环节内的角色由于某些原因不能一直保持着工作状态,会导致毕业论文完成的停滞。
为了避免这种情况的发生,为方便教师、学生和管理者顺利完成对应角色的任务,高校需要一个专业的针对毕业论文的管理系统把完成毕业论文的所有操作都集中到一个系统中。
本文的主要工作是根据高校教育管理的迫切需求,研究了毕业论文完成的整个过程,最终实现了一个基于Web的高校毕业论文管理系统。
在这个管理系统系统中,所有角色都可以在线上进行任务的完成,所有的角色都可以在线进行交流。
所有角色都可以在线查看当前时间段需要完成的任务,毕业学生可以在线上传该阶段任务的文档,导师也可以方便地在线对学生的任务文档进行批阅及提出意见和建议,专业负责人可以线上安排答辩小组,院级管理员和校级管理员可以分配管理每个角色的权限及维护系统。
毕业论文中所有的工作都集中在基于Web的高校毕业论文管理系统中,大大方便了所有角色的工作完成,加快了毕业论文完成的效率,也提高了毕业论文完成的质量。
```

源码获取： [**点此下载**](http://www.shuyue.fun/?type=productinfo&id=178)
 
#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目 
6.数据库：MySql 8.0版本；
```

#### 技术栈
```
1. springboot + theamleaf + mysql8.0
```

#### 使用说明
```
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中application.yml配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，浏览器中输入http://localhost:8080/thesis/ 登录
5. 管理员账户admin  密码123456
教师账号：2201604858,密码123456
学生账号：0164809,密码123456
```

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/195903_d3b10e67_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/195913_c2b72891_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/195924_7f245b39_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/195930_95c78656_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/195940_2cb94930_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/195949_d63f831a_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/195958_4cf88389_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/200005_09593bb9_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/200014_1813c3cd_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/200024_f52ac79c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/200032_d80c9041_863230.png "屏幕截图.png")

