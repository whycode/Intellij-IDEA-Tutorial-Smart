# Intellij IDEA 学习指南

## 编写这套教程的理由
> *理由1：公司和个人使用Intellij IDEA 的趋势在逐渐增多，增长速度迅猛，但是相关教程太少，除了官网教程，急需这样的图文教程。
> *理由2：Intellij IDEA 开源社区群，每次新人进群，重复的问题问了一遍又一遍。
> *理由3：自己在学习使用Intellij IDEA 的过程中，遇到的各种坑，不想后来的学习者再遇到，避免少走弯路，快速上手Intellij IDEA.
> *理由4：自己在学习过程中别人帮助我很多，编写这套图文教程是为了感谢他们，同时实践一下开源的精神，希望也可以借此推广Intellij IDEA。
> *理由5：个人的小私心。想通过编写这套图文教程，来锻炼一下自己的编写文档能力。

## 学习使用Intellij IDEA 的好处
> * 简单的罗列一下使用好处
> * 1. 智能的代码补全功能，支持首字母匹配，支持中间字母单词匹配，支持尾部字母匹配等，支持 java html，css,js，JQuery等语言的代码提示。
> * 2. 强大的索引功能和视图功能,文件快速定位，文件默认自动保存，简单直接的查看类或接口的信息:比如继承，实现等。
> * 3. 强大的编辑功能和重构功能，支持列编辑，快速选中当前变量等。
> * 4. 全面的快捷键操作,idea 里面的各种操作基本都可以通过快捷键完成，而且快捷键非常通俗好记，可以真正实现脱离鼠标，全键盘操作，享受在键盘上飞一般的感觉和快感。
> * 5. 各种语言支持非常好，特别是HTML,CSS,JS，轻松定位样式和JS代码提示.
> * 6. 集成各种当前主流构建项目的工具：ant,maven,gradle，无需再下插件。
> * 7. 集成各种当前主流版本控制的工具：svn,git和gitHub，无需再下插件。
> * 8. 自带java 反编译功能，可以直接查看第三方Jar包的源码，自动提示是否下载Jar的source.
> * 9. 支持各种数据库连接功能，mysql,SQL,Oracle等.
> * 10. 支持当前主流的框架和最新的技术，比如Docker等.
> * [更多详细特性](Intellij-IDEA-Features.md)

## 个人学习的经历




## 十条学习建议
> * 第一条：熟练学会使用Intellij IDEA 需要时间,不能急于求成。
在使用Intellij IDEA 的时候，要知道上手这个工具很，保守估计学会Intellij IDEA 的基本操作起码一个月以上。
第一：国内好的资料和教程很难。第二：虽然官方提供详细的资料，可惜都是全英文的。这导致使用Intellij IDEA 的学习成本有点高。
但是这不代表没有去学习使用Intellij IDEA 的价值。这款号称“The Most Intelligent Java IDE”,并不是浪得虚名的，当你真正会使用的时候，我相信你肯定会爱上它，因为它太好用，太智能，太任性话了。
在你还没有熟悉Intellij IDEA 的时候，尽量不要去修改Intellij IDEA 的设置和搞特殊私人化的操作，比如修改主题，修改样式，定做模板等操作，除非必要的设置，不然一旦出现问题，你讲会无从下手的。

> * 第二条：不要无视Intellij IDEA 的英文错误提示
在使用Intellij IDEA 的时候，你肯定会碰到各种各样的错误，不过你不用担心。
Intellij IDEA 基本上都给你一个错误英文的提示，请不要无视英文提示,当做没看见,如有需要自备英文词典进行翻译。
基本上明白了错误提示上的意思，问题解决起来也很方便，想别人请教和帮助的时候也能得到快速的回答。
尽量用google 附上英文错误提示的内容，去搜索解决办法的答案。

> * 第三条：Eclipse 使用者请先了解Eclipse和Intellij IDEA 的基本区别
An Eclipse workspace is similar to a project in IntelliJ IDEA
An Eclipse project maps to a module in IntelliJ IDEA
An Eclipse project-specific JRE maps to a module JDK in IntelliJ IDEA
An Eclipse user library maps to a global library in IntelliJ IDEA
更多详情请看官方`Eclipse FAQ`：<https://www.jetbrains.com/idea/help/eclipse-faq.html>

> * 第四条：请不要带上使用Eclipse的坏习惯
为什么我要说：请不要带上使用Eclipse的坏习惯？在Eclipse中形成的好习惯，可能用在intellij IDEA 就变成坏习惯了。因为 Eclipse 跟Intellij IDEA 两个是一个不同的IDE工具,所以其中的软件的理念和行为习惯大不相同。
而把eclipse的习惯和想法带到使用Intellij IDEA 上面来，非但不能事半功倍，反而会阻碍你使用Intellij IDEA，陷入各种麻烦，最好的办法就是把它当然一个你完全不知道的软件来进行学习。
对于那些使用Myeclipse 或Eclipse的时间比较久的开发者，学习Intellij IDEA 起来可能相对而言比较困难，因为那种Eclipse的想法和思维根深蒂固，一时间很难改正过来。
所以我尽可能把我所知道的Eclipse和IntellijIDEA 使用上的差别写出来。当 如果相同功能，在Eclipse和Intellij IDEA 上实现不同时，我也会进行适当说明。

> * 第五条：请掌握项目目录中文件夹颜色和class图标的含义
在Eclipse中文件是没有颜色，但是在Intellij IDEA 是有颜色区分，不同的文件颜色代表的不同含义，比如：![icon](images/guide/icon-directory.png),![icon](images/guide/icon-package.png),![icon](images/guide/icon-source-root.png),![icon](images/guide/icon-test-root.png),![icon](images/guide/icon-excluded-root.png),![icon](images/guide/icon-resources.png),![icon](images/guide/icon-test-resources.png),![icon](images/guide/icon-generate-source-roots.png),![icon](images/guide/icon-generate-test-roots.png)
还有Intellij IDEA 的class都是有图标的，不同类型的class有不同的图标,比如：![icon](images/guide/icon-class.png),![icon](images/guide/icon-excluded-class.png),![icon](images/guide/icon-out-soure-root.png)
具体含义请看教程,如果不掌握好这些文件颜色和class图标的话，这会直接影响你的项目由于个人的误操作导致项目无法正常运行，但是这些错误是没有错误提示的。

> * 第六条:自备VPN加速器和了解maven的基本知识
1.Intellij IDEA 的使用跟网络的好坏有很多关系。由于 IntelliJ IDEA 官网服务器设置在国外，且官网用到一些类似 youtube，Facebook 等站时,会使得你在国内出现访问巨慢或是无法访问的特殊情况，无法有效的学习Intellij IDEA。
此外，在Intellij IDEA 使用过程中涉及到访问插件库，在线下载并安装,在线更新Intellij IDEA 等操作时，很有有可能导致失败，还有对maven 工程的项目进行操作，更新某些依赖时，默认的中央仓库地址在国外，这会导致有些依赖JAR无法下载。(虽然可以通过切换maven 仓库镜像来解决,但是开源中国的JAR不全)
。所以请自备VPN等网络加速工具。
2.Intellij IDEA 中很多地方都运用到maven的思想，比如项目的设置，Aritfacts,Facets,Modules等,还有在 Intellij IDEA 里面直接搜索JAR 进行下载,用好Intellij  IDEA离不开Maven的知识的支持。

> * 第七条:不要试图汉化Intellij IDEA 菜单
虽然网上有能部分汉化Initellij IDEA 菜单的插件，但是对Intellij IDEA 的支持不是很好，会出现使用上的问题，到底部分菜单中的操作失灵，也不利于对Intllij IDEA的学习。

> * 第八条：实际开发工作者不要随意更新Intellij IDEA的版本
官方正式稳定版列表:<https://confluence.jetbrains.com/display/IntelliJIDEA/Previous+IntelliJ+IDEA+Releases>
一般现在主流的IntelliJ IDEA 版本是13 和 14.但是在设置上存在差异,14 版本 IntelliJ IDEA 对13 版本 IntelliJ IDEA的setting界面进行整合，合并了Project Setting 和IDE Setting. 但是细节设置上所沿用的介绍是没有多大改变的。
其中旗舰版（Ultimate Edition）为收费版本，有 30 天试用期。如果你是学生、老师、开源项目参与者都可以向官网免费试用旗舰版.
Intellij IDEA  的小版本迭代速度很快，如没必要，在实际工作中尽量不要随便更新，确保稳定性是重要的，以免出现问题。如果要更新Intellij  IDEA 不推荐在线更新。除非你的网路是OK的。

> * 第九条：请尝试学习官网的30天快速入门手册
 Quick Start：<https://www.jetbrains.com/idea/help/intellij-idea-quick-start-guide.html>
 第一：可以锻炼你阅读英文文档的能力。
 第二：掌握更多，更全面的操作Intllij IDEA 细节和新功能。
 本套教程只是起到引导的作用，告诉你一些Intellij IDEA 的基本常识和运作的原理，最好的教程和资料还是来自于官网。

> * 第十条：希望你对本套教程提出宝贵的意见
如果你发现本套教程中存在错误，请及时联系我。
如果在某一个功能模块，你更好的方法和想法，也可以及时联系我。
如果你自己有写关于Intellij IDEA 的文章，也可以及时联系我。
总之你有好的想法和建议,都是可以联系我。

## 教程适用的对象
> *  零基础的java 初学者,没有使用过Myeclipse ,Eclipse.
> *  有基础的java 开发者,有工作经验的Java开发者,使用过Myeclipse ,Eclipse,使用时间2年以内.
> *  资深java开发者,使用过Myeclipse 或Eclipse的时间在3年以上.

## 教程的简单说明
本套教程分为六个大章节分别是：
> * 一.Intellij IDEA 初体验（新手必看）
> * 二.Intellij IDEA 基本常识（新手必看）
> * 三.版本控制篇（参加工作者必学）
> * 四.搭建项目篇（有Java SE 基础者，最好有Java EE 基础）
> * 五.疑难杂症篇（使用Intellij IDEA 中遇到问题，求助篇）
> * 六.拓展篇（掌握Intellij IDEA 基本功能,且使用时间超过1个月以上）
> * 重要说明：本套教程以图文配上必要的文字说明进行展开。
在`Intellij IDEA 初体验`和`Intellij IDEA 基本常识`这两章节中，考虑到初学者的学习困难，尽可能一步一图。在后面的章节中，只添加操过程中关键步骤的截图，省略非关键的步骤截图。
教程中,我尽可能引用Intellij  IDEA自带的帮助手册的英文说明。

## 本套教程所用工具版本说明
> * 重点说明：本套教程主要在windows 7 64位操作系统下进行演示，采用的当前最新的稳定版`ideaIU-14.1.4`，免费试用30天进行演示。
> * Intellij IDEA 的版本：`ideaIU-14.1.4`
> * JDK版本：`jdk-7u80-windows-x64`
> * Maven：`apache-maven-3.0.5`
> * Gradle：` gradle-2.3`
> * Tomcat：`apache-tomcat-7.0.62`
> * 注：适用用于 ` Intellij  IDEA  14 系列 `

## 感谢重要的人
> * 10年资深Intellij IDEA 使用者，我称之为"活的IDEA"：大师傅（梅老板）
> * Intellij IDEA  使用重度发烧友，狂热追求者，良心博客群主：Youmeeek
> * 资深前端工程师：林家小少
> * Intellij IDEA 开源社区群：全体人员

## 友情链接
Youmeeek:<http://www.youmeek.com/>