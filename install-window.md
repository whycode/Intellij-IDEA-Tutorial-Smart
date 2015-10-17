##  Windows 系统下安装 IntelliJ IDEA

### 本套教程所用工具版本说明
> * Intellij IDEA 的版本：`ideaIU-14.1.4`
> * JDK版本：`jdk-7u80-windows-x64`
> * Maven：`apache-maven-3.0.5`
> * Gradle：` gradle-2.3`
> * Tomcat：`apache-tomcat-7.0.62`
> * 注：适用用于 ` Intellij  IDEA  14 系列 `

### 官方系统配置要求
> *  Microsoft Windows 8/7/Vista/2003/XP (incl.64-bit)
> *  1 GB RAM minimum, 2 GB RAM recommended
> *  300 MB hard disk space + at least 1 G for caches
> *  1024x768 minimum screen resolution
> *  JDK 1.6 or higher

### 系统环境变量配置要求
> *  配置JAVA_HOME的环境变量(`JDK 1.6` 以上)
> *  构建Maven 项目，请先配置Maven的环境变量(`可选`，Intellij 14 以上版本自带 maven 3 和 maven 2 版本)
> *  构建Gradle 项目，请先配置Gradle 的环境变量(具体操作百度)

### 官方下载地址
> *  Intellij IDEA:  <https://confluence.jetbrains.com/display/IntelliJIDEA/Previous+IntelliJ+IDEA+Releases>
> *  JDK 1.6 :  <http://www.oracle.com/technetwork/java/javasebusiness/downloads/java-archive-downloads-javase6-419409.html#jdk-6u21-oth-JPR>
> *  JDK 1.7 :  <http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html>
> *  JDK 1.8 :  <http://www.oracle.com/technetwork/java/javase/downloads/index.html>
> *  Maven   : <http://maven.apache.org/download.cgi>
> *  Gradle  :  <http://gradle.org/gradle-download/>

### 首次安装
> *   Intellij IDEA 安装速度很快，非常简单。基本都是默认下一步即可，如有不同，会有特殊说明。

#### 第1步
![第1步](images/installs/windows/i-w-install-one.png)
#### 第2步
![第2步](images/installs/windows/i-w-install-two.png)
#### 第3步
![第3步](images/installs/windows/i-w-install-three.png)
#### 第4步
![第4步](images/installs/windows/i-w-install-four.jpg)
> *  编号1：勾选，表示创建桌面快捷方式。
> *  编号2：勾选后表示默认打开java文件和groovy使用Intellij IDEA 打开，建议不勾选。


####  第5步
![第5步](images/installs/windows/i-w-install-five.png)

####  第6步
![第6步](images/installs/windows/i-w-install-six.png)

####  第7步
![第7步](images/installs/windows/i-w-install-seven.png)
> * \(^o^)/ 恭喜你! 安装成功，点击`Fish`立即启动,赶紧投入Intellij  IDEA 的怀抱吧。

### 首次启动

#### 启动画面
![启动画面](images/installs/windows/i-w-set-start-page.png)
#### 第1步 选择Intellij IDEA 的配置文件
![启动画面](images/installs/windows/i-w-set-software-config.jpg)
> * 进入Intellij IDEA 软件的配置文件的选择目录.
1.如果首次安装，直接选择'OK'。
2.如果第二次安装，如果想使用以前Intellij IDEA 的配置文件，请选择①
> * 这个配置文件默认生成的目录：C:\Users\ 用户名\.IntelliJIdea14

#### 第2步 输入秘钥或试用30天
![第10步](images/installs/windows/i-w-set-license-activation.png)
> * 上图编号1：购买正版的授权码。如果你是一个有情怀的开发者，请购买正版，支持 一下Intellij IDEA。[官方购买地址](https://www.jetbrains.com/idea/buy/)
> * 上图编号2：试用30天。适合学生和初次接触的开发者
> * 注：如果有疑问，请加<a target="_blank" href="http://shang.qq.com/wpa/qunwpa?idkey=cf27f5debc95d432ec9192af231e837587949fe964b8179e1a0670d8e4690f7d"><img border="0" src="http://pub.idqqimg.com/wpa/images/group.png" alt="IDEA 后端开发 (10106666)" title="IDEA 后端开发 (10106666)"></a>。

#### 第3步 同意协议
![第11步](images/installs/windows/i-w-set-accept-agreement.png)
#### 第4步 选择主题(UI Themes)
![第12步](images/installs/windows/i-w-set-select-theme.jpg)
#### 第5步 默认插件（Default plugins）
![第13步](images/installs/windows/i-w-set-default-plugins.png)

> ##### 对上图中的编号进行简单的说明

> ##### 编号1 :Java Frameworks
>  ![第13步](images/installs/windows/i-w-set-default-plugins-java-frameworks.png)
> ##### 编号2 :Build Tools
>  ![第13步](images/installs/windows/i-w-set-defualt-plugins-build-tools.png)
> ##### 编号3 :Web Development
>  ![第13步](images/installs/windows/i-w-set-defualt-plugins-web-development.png)
> ##### 编号4 :Version Controls
>  ![第13步](images/installs/windows/i-w-set-defualt-plugins-version-controls.png)
> ##### 编号5 :Test Tools
>  ![第13步](images/installs/windows/i-w-set-defualt-plugins-test-tools.png)
> ##### 编号6 :Application servers
>  ![第13步](images/installs/windows/i-w-set-defualt-plugins-application-servers.png)
> ##### 编号7 :Clouds
>  ![第13步](images/installs/windows/i-w-set-defualt-plugins-clouds.png)
> ##### 编号11 :Other Tools
>  ![第13步](images/installs/windows/i-w-set-defualt-plugins-other-tools.png)
#### 第6步 功能插件 （featured plugins）
![第14步](images/installs/windows/i-w-set-featured-plugins.png)
#### 第7步 进入 Intellij  IDEA  欢迎界面
![第15步](images/installs/windows/i-w-set-welcome-to-Intellij-idea.png)

## 已有旧版本安装新版本

![已有旧版本安装新版本步骤截图](images/installs/windows/iii-b-repeatedly-install-1.jpg)

![已有旧版本安装新版本步骤截图](images/installs/windows/iii-b-repeatedly-install-2.jpg)

> * 上图，显示我目前电脑中已经有一个 IntelliJ IDEA 版本，如果我勾选了标记 1，则表示安装之前会先卸载掉电脑上的旧版本。
> * 上图标记 2，如果勾选了，则 IntelliJ IDEA 在卸载旧版本的时候直接删除掉你旧版本的个性化设置，`（慎重勾选）`。
> * IntelliJ IDEA 是支持一台电脑装多个大版本的。比如可以同时装` Intellij IDEA 13 系列的版本`和`Intellij IDEA 14 系列的版本`。
> * 接下来的步骤我们假设勾选了标记  1 再进行安装。

![已有旧版本安装新版本步骤截图](images/installs/windows/iii-b-repeatedly-install-3.jpg)

> * 上图，由于上一步勾选了卸载旧版本选项，所以出现了选择删除旧版本的配置选项。
> * 第一个选项：删除旧版本的缓存和本地历史记录。`（慎重勾选）`
> * 第二个选项：删除旧版本的个人个性化设置。`（慎重勾选）`
> * 点击 uninstall，进入全自动的卸载过程，卸载完成接下来的步骤跟上文`首次安装`一致，这里不再进行说明。

## 卸载

> * 卸载过程完整截图

![卸载](images/installs/windows/iii-c-uninstall-1.jpg)

![卸载](images/installs/windows/iii-c-uninstall-2.jpg)

![卸载](images/installs/windows/iii-c-uninstall-3.jpg)

