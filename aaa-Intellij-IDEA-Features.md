# Intellij IDEA 功能特性

##  Intellij IDEA 13 新特性包括：
2013年，IntelliJ IDEA小组已经与众多业内领先的开发技术建立了非常紧密的关系：例如Android, Spring, Scala和Gradle. 这样一来，我么就能够在百舸争流中保持领先，为您提供最优质的开发工具，让您体验到最尖端的开发技术
![icon](images/features/intellij-idea-13.png)

#### JavaEE 7
- 为了兑现我们“最先”而且“最优”地为所有Java开发者提供新技术支持的诺言，IntelliJ IDEA 13 全面支持Java EE 7——Oracle最新推出的企业Java平台。在最新版本的Intellij IDEA中，我们为CDI 1.1， JSF 2.2，JAX-RS 2.0, 批处理和其他新规范提供代码补全支持。同时，我们还提供对新版本应用服务器的支持，
例如GlassFish 4, Wildfly(就是原来大名鼎鼎的JBoss——译者注）， Tomcat 8等等。要了解更多的信息，请看这个介绍视频

#### Spring
-  Spring开发这回在新版本的IntelliJ IDEA中获得比以往更多的帮助，有了全新的Spring工具窗口，能够让用户更加便捷地在项目中上下文配置和其对应的bean类之间导航。这个新的工具窗口还能够让用户方便地浏览MVC控制器和其对应的URL映射。IntelliJ IDEA 13同时还优化了性能，并简化了Spring项目的配置。

#### Android
-  2013年Google I/O大会上，最令人惊艳之处之一就是预览版的Android Studio , 一个全新的Android集成开发环境。Android Studio是以IntelliJ IDEA开源社区版本为基础开发而成。这个利器的推出吸引了大批热情的Android开发人员，正是他们帮助IntelliJ平台取得了长足的进步，
并丰富了很多功能特性。IntelliJ IDEA 13是在Android开发者的帮助和督促下推出的首个主要发行版本，它在代码编辑器，UI设计器，SQLite数据库接入支持等很多方面都有很大的改进。

#### Gradle
- 另一个IntelliJ IDEA 13的重要功能强化是重新定义了对Gradle的支持，包括改进了对项目同步功能，对依赖项和插件的代码自动补全功能，快速文档功能，和代码生成功能。IntelliJ IDEA 13甚至能够通过Gradle file自动配置Web faces和WAR发布包。用户可以从这个介绍视频浏览一下Gradle的支持功能。

#### 用户界面
- 去年，IntelliJ IDEA为用户带来了暗色而时髦的界面主题（Darcula Theme——译者注）；这次， 我们IntelliJ IDEA开发小组致力于让整体用户体验更加直接和有效：新设计的“任意处搜索”功能，Presentaion和Lens模式，这些特性都让整个IDE的搜索功能更加迅速。
另外，工具栏和工具窗口的按钮都被设计成了默认隐藏状态，这趟能够为主屏幕流出宝贵的空间。当然，还有更酷的：全新的Linux亮色主题(该主题是开源社区版本的默认主题——译者注），以及专门为Linux用户设计的全屏模式。
IntelliJ IDEA 13 Community版真实界面（Darcula主题）

#### 数据库
- 在应用程序开发过程中，访问各种不同的数据库，以获取存储数据，是非常重要的工作，正式充分考虑到这一点，IntelliJ IDEA 13 提供了改进后的数据处理工具。 数据库工具中提供了简化的数据源配置功能，新的结构化视图，便捷视图，还提供了对数据表中主键和外键进行导航的操作, SQL语句代码补全，以及查询过滤器等等，总之有很多新的功能。

#### 其他值得关注的
- 增强型调试器
- 更好的性能
- 对Groovy支持做了改进
- 内置SBT集成的Scala语言支持
- 为Web开发提供了新工具，包括Javascript代码覆盖工具，Stylus和Compass支持
- 全新内置的终端工具窗口
- CLoudFoundry 2.0, OpenShift和Heroku开发工具
- 中文原文链接:<http://www.importnew.com/7572.html>
- 英文原文链接:<http://blog.jetbrains.com/idea/2013/12/intellij-idea-13-is-released-work-miracles-in-java-and-beyond/>

##  IntelliJ IDEA 14导航特性Top20

![icon](images/features/Intellij-idea-14.png)
#### Java Debugger：
-  采用新API完全重写了Debugger。为所有编程语言使用统一的Debugger工具栏（窗口）。
-  Watches窗口支持保存表达式（关闭窗口依然会记录上次填入的表达式）
-  支持按用户组排列断点。
-  长数组或大集合的隐藏元素可以根据需要进行展示，不再需要通过视图参数进行设置。

#### Java编辑器：
-  智能Backspace缩进：按下Backspace，会根据代码格式化参数进行格式化。因此在脱字符(^)前删除缩进时不会打乱代码。
-  支持为方法生成测试，并添加到现有的测试类。

#### 通用IDE:
-  新的Code cleanup（选择Analyze → Code Cleanup 或者在VCS commit对话框中设置）可对选中的文件在批量模式下进行自动纠正（quick-fixes）。
-  改进了Find in path可在搜索扩展名未知文件，搜索范围包括.idea配置中的所有文件。在搜索字符串中包含的标识符（3个或更多字符）时，会返回匹配的结果。
-  无需额外安装插件即可拷贝/粘贴选中代码为HTML/RTF格式。
-  缩短了IDE启动时间。

#### JavaFX:
-  集成了SceneBuilder 2.0为UI designer，不再需要离开IntelliJ IDEA去编辑.fxml文件（该功能要求IntelliJ IDEA在Java 8环境下运行）。

#### Spring:
-  开发Spring项目时，显著改善了编辑大量XML描述符文件的性能。
-  Select In也可以展示Spring tool窗口。
-  新的插件支持Spring Websocket。

#### 优化了Grails和Gradle的协同工作。

#### Mercurial:
-  改进了Push对话框。
-  Log viewer加载更快速。
-  在Log viewer中恢复当前改变时，增加恢复未提交的merge和update选项。
-  在Log viewer中显示当前版本信息。
-  许多其他改进，包括incoming/outgoing变化通知。

#### Web开发：
-  支持JavaScript输入后代码补全。
-  Spy.js和Node.js现在可以通过新的运行配置一起工作。
-  中文原文链接:<http://www.importnew.com/15462.html>
-  英文原文链接:<https://dzone.com/articles/new-article-about-testing-javafx-apps-with-testfx-1>

## 关于更多Intellij IDEA 特性信息
> * IntelliJ IDEA 14.1 is Here! <https://www.jetbrains.com/idea/whatsnew/>
> * IntelliJ IDEA 14.1.4 Release Notes: <https://confluence.jetbrains.com/display/IDEADEV/IntelliJ+IDEA+14.1.4+Release+Notes>
> * What's New in IntelliJ IDEA 14 and 14.1? <http://blog.jetbrains.com/idea/2015/03/intellij-idea-14-1-is-here//>
> * All Intellij IDEA Release NOtes: <https://confluence.jetbrains.com/display/IDEADEV/Home>
> * 解析IntelliJ IDEA内部设计:<http://www.importnew.com/14260.html>
> * 借助IntelliJ IDEA提高开发效率:<http://www.infoq.com/cn/presentations/intellij-idea-tips>
