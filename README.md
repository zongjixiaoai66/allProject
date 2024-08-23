# 项目汇总
3300套JAVA毕业设计项目成品源码，需要的同学请自行下载~
【获取方式1】 百度网盘：https://pan.baidu.com/s/1BmRAWyo5IZ-NDw52OBtp9w?pwd=l9ag

【获取方式2】 夸克网盘：

链接：https://pan.quark.cn/s/dd5057677bb2

提取码：RXbB

# 启动安装包

https://pan.baidu.com/s/1s51E22bl8JoFoc1D-Qja1Q?pwd=ajhb

1【apache-maven-3.8.4.zip、S系列Maven依赖.zip】
Maven是后端项目的构建工具。比如项目用到了SpringBoot依赖，我们可以将SpringBoot的Jar包依赖都下载下来，放到项目，这样会造成需要备份的代码体积过大。

所以一般使用Maven构建的方式，将需要使用的后端依赖定义到pom.xml中，由Maven自动去下载依赖的Jar包，从而实现后端项目的构建部署。

同学们可以下载该文件，直接解压到本地目录即可，路径不要有中文或空格，然后在IDEA完成配置。

另外我也提供了现成的依赖文件【T系列Maven依赖.zip】，同学们只需解压到本地，IDEA配置一下本地仓库就可以了，如果不需要也可以自己慢慢下载。

2【HeidiSQL_12.1.0.6537_Setup.exe】
使用该软件的前提是MySQL8已经正确安装，切记是8.0版本！！！不能是5.7！！！

HeidiSQL是一个数据库可视化工具，因为我提供的SQL文件都是用这个工具导出的，所以同学们也需要用这个工具导入数据库，否则可能出现兼容性问题。

数据库SQL文件导入之后，如果数据表中有数据则说明导入成功。

在确保数据库初始化成功后，同学们就可以使用其他软件（如Navicat）去查询数据库。

该软件也可以从官网下载最新版本，但会比较慢：https://www.heidisql.com/download.php

3【ideaIU-2022.1.4.exe】
IDEA是开发后端必备的工具，UP提供的破解文件最高支持2022.1版本，所以提供了这个版本的安装包。

同学们只要保证版本在2021.2及以上即可，且非开源社区版，因为低于这个版本不支持JDK17的配置，导致项目无法启动。

该软件也可以从官网下载最新版本，https://www.jetbrains.com.cn/idea/download/other.html

4【Idea操作工具202201版本.zip】、【IDEA激活码2508.txt】
IDEA安装完成后，不能直接打开，需要先执行操作工具（解压密码123456）的scripts的install-current-user.vbs文件。

等待执行完成（Done的弹框）完成后，才可以启动IDEA，顺序不能错位，如果错位会导致无法破解成功，需要卸载IDEA重装。

如果VBS文件提示无权限等报错，需要用管理员身份的CMD窗口，使用命令执行VBS程序。

IDEA启动后，输入激活码就可以进入IDEA，激活码时限到25年8月为止。

5【jdk-17_windows-x64_bin.exe】
项目后端需要使用JDK，所以需要同学们安装JDK。

请注意安装完成后，IDEA需要引用这个JDK版本哦，T系列项目可以用JDK8，也可以用JDK17。

6【mysql-installer-community-8.0.38.0.msi】
数据库文件，直接双击安装即可，只需要安装Server服务，配置的密码不建议有特殊字符（否则后端uml中需要转义，避免不必要的麻烦），个人学习建议123456或root


7【node-v14.21.3-x64.msi】
前端项目的Node.JS环境，建议使用14版本，不能使用淘宝镜像或cnpm，否则会出现依赖下载不全的情况。

首先 npm i -g @vue/cli，再cd到front目录，输入 npm i 拉取前端依赖，最后 npm run dev 运行。

具体请看启动教程：https://space.bilibili.com/417412814/channel/collectiondetail?sid=2242844

如果出现报错，有mkdir关键词  说明你的cmd无权限，可以用管理员身份的cmd再试。

如果出现 timeout 关键词，说明你当前的网络无法连接npm仓库，建议多试几次，或换网络（如热点），或过段时间再试。

如果你的电脑部署了多个项目，且项目需要不同的Node版本，可以用NVM，安装包也提供了【nvm-setup.exe】

如果你还是不会部署，可以用nginx完成，安装包【nginx.zip】

9【VSCodeUserSetup-x64-1.76.1.exe】
VSCode是前端的开发工具之一，VSCode里面建立的终端效果，等同于cmd窗口，但好处是可以一边改代码，一边看项目启动状态。

如果同学们只需要启动项目应付检查，不需要安装VSCode，直接cmd启动即可，反之则需要安装。
