# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0750springboot人职匹配推荐系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=106)


# 第一章 绪 论
1.1背景及意义

系统管理也都将通过计算机进行整体智能化操作，对于人职匹配推荐系统所牵扯的管理及数据保存都是非常多的，例如管理员；首页、个人中心、用户管理、企业管理、岗位信息管理、岗位类型管理、应聘信息管理、应聘状况管理、平台费用管理、系统管理，用户；首页、个人中心、应聘信息管理、应聘状况管理、我的收藏管理，企业；首页、个人中心、岗位信息管理、应聘信息管理、应聘状况管理、平台费用管理，前台首页；首页、企业、岗位信息、新闻资讯、个人中心、后台管理等功能，这给管理者的工作带来了巨大的挑战，面对大量的信息，传统的管理系统，都是通过笔记的方式进行详细信息的统计，后来出现电脑，通过电脑输入软件将纸质的信息统计到电脑上，这种方式比较传统，而且想要统计数据信息比较麻烦，还受时间和空间的影响，所以为此开发了人职匹配推荐系统；为用户提供了方便管理平台，方便管理员查看及维护，并且可以通过需求进行内容的编辑及维护等；对于用户而言，可以随时进行查询所需信息，管理员可以足不出户就可以获取到系统的数据信息等，而且还能节省用户很多时间，所以开发人职匹配推荐系统给管理者带来了很大的方便，同时也方便管理员对用户信息进行处理。

本论文人职匹配推荐系统主要牵扯到的程序，数据库与计算机技术等。覆盖知识面大，可以大大的提高系统人员工作效率。

1.2国内外研究概况

随着国内经济形势的不断发展，中国互联网进入了一个难得的高峰发展时期，这使得中外资本家纷纷转向互联网市场。 然而，许多管理领域的不合理结构，人员不足以及市场管理需求的增加使得更多的人具备了互联网管理的意识。

在当今高度发达的信息中，信息管理改革已成为一种更加广泛和全面的趋势。 “人职匹配推荐系统”是基于Mysql数据库，在SpringBoot框架程序设计的基础上实现的。为确保中国经济的持续发展，信息时代日益更新，人职匹配推荐系统仍在蓬勃发展。同时，随着信息社会的快速发展，各种管理系统面临着越来越多的数据需要处理，如何用方便快捷的方式使管理者在广阔的数据海洋里面查询、存储、管理和共享有效的数据信息，对我们的学习，工作和生活具有重要的现实意义。因此，国内外学术界对此进行了深入而广泛的研究，一个新的研究领域——人职匹配推荐系统诞生了。

28

1.3 研究的内容

目前许多人仍将传统的纸质工具作为信息管理的主要工具，而网络技术的应用只是起到辅助作用。在对网络工具的认知程度上，较为传统的office软件等仍是人们使用的主要工具，而相对全面且专业的信息管理软件仍没有得到大多数人的了解或认可。本选题则旨在通过标签分类管理等方式，实现人职匹配推荐系统的各种功能，从而达到对人职匹配推荐系统的管理。

详细内容介绍，将在以下六章中详细阐述：

第一章、绪论，介绍了研究课题选择的背景及意义、研究现状，简要介绍了本文的章节内容。

第二章、引入技术知识，通过引入关键技术进行开发，向系统中涉及直观表达的技术知识。

第三章、重点分析了系统的分析，从系统强大的供需市场出发，对系统开发的可行性，系统流程以及系统性能和功能进行了探讨。

第四章、介绍了系统的详细设计方案，包括系统结构设计和数据库设计。

第五章、系统设计的实现，通过对系统功能设计的详细说明，论证了系统的结构。

第六章、系统的整体测试，评判系统是否可以上线运行。


2. # 关键技术的研究
## 2.1相关技术
人职匹配推荐系统是在Java + MySQL开发环境的基础上开发的。Java是一种服务器端脚本语言，易于学习，实用且面向用户。全球超过35％的Java驱动的互联网站点使用Java。MySQL是一个数据库管理系统，因为它的体积小但速度快，成本低，或者开源受到中小型网站的青睐。因此，Java + MySQL作为一个成熟的开发环境，可以满足人职匹配推荐系统设计和开发所需的稳定性，安全性和可扩展性要求。
## 2.2 JAVA技术
JAVA语言是目前软件市场上应用最广泛的语言开发程序。可以在多种平台上运用的，兼容性比较强，适应市面上大多数操作系统，不会出现乱码的现像，其扩展性和维护性都更好，具有分析问题和解决问题的能力，是面向过程的程序设计方便我们编写的代码更强壮。

JAVA相对其它语言来说，比较简单，编译起来更方便一些，安全可靠性高。不完全统计，现在全世界大约有2000多万人在使用它，JAVA既可以镶嵌使用又可以独力的使用。JAVA大致可以分成两个部分，一种部分是JAVA负责的编译，另一种是JAVA负责的运行。JAVA和C++语言很相像，但JAVA在编程时是一种以对象为导向的方式来进行编译的，使得编出来的软件可以单机使用，也可以在互联网上使用，检查出错更为方便。JAVA分布式、体系结构中立的特点也使得其存储更快，编议更简单。面向对象包括四个特点，一是封装，就是说在定义类的时候可以实现一定的功能和属性。二是抽象，属于类的一种，可以把一个具有共同属性的类封装在一个抽象里，便于简单编议。三是继承，顾名思义就是带有前者的特性。还有一个就是多态的特点，可以多种一起运用，表现了它可扩展性好。
## 2.3 MySQL数据库
数据库是系统开发过程中不可或缺的一部分。 在WEB应用方面，MySQL AB开发了一个具有很大优势的MySQL关系数据库管理系统。 MySQL可以将数据存储在不同的表中，这非常灵活，并且还可以提高系统在实际应用中的速度。 数据库访问最常用于标准SQL语言，MySQL用于SQL语言，因此它具有高度兼容性。数据库的操作是必不可少的，包括对数据库表的增加、删除、修改、查询等功能。现如今，数据库可以分为关系型数据库和非关系型数据库，Mysql属于关系性数据库，Mysql数据库是一款小型的关系型数据库，它以其自身特点：体积小、速度快、成本低等，Mysql数据库是目前最受欢迎的开源数据库。
## 在WEB应用技术中， Mysql数据库支持不同的操作系统平台，虽然在不同平台下的安装和配置都不相同，但是差别也不是很大，Mysql在Windows平台下两种安装方式，二进制版和免安装版。安装完Mysql数据库之后，需要启动服务进程，相应的用户就可以连接数据库，用户可通过命令行或者图形界面工具登录数据库。
## 2.4 Tomcat介绍
Tomcat 虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML页面的运行提供技术支持，Tomcat 的任务则是运行Servle和Java 页面。Tomca也具有一定的HTML页面处理功能。Tomcat属于一种轻型的服务器，所以说在中小企业中并不具有普适性。但是当程序员需要开发或调试Java 程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML 页面进行访问。Tomcat是非常受欢迎的服务器，因为它具有较好的扩展性，而且在运行的时候不需要太多的系统资源，拥有程序员所需要的收发邮件功能，还能够支持负载平衡，该程序能够不断的更新，程序员能够根据自己的需要增加新的功能。

## 2.5 SpringBoot框架
Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。
Spring Boot特点：
1、创建一个单独的Spring应用程序；
2、嵌入式Tomcat，无需部署WAR文件；
3、简化Maven配置；
4、自动配置Spring；
5、提供生产就绪功能，如指标，健康检查和外部配置；
6、绝对没有代码生成和XML的配置要求；
`  `安装步骤：
`   `最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。 为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。 可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。 更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。 可以从GVM命令行GVM install springboot安装Boot及其CLI。 在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brew tap pivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。


# 第三章 系统分析
## 3.1 系统设计目标
人职匹配推荐系统主要是为了用户方便对应聘信息、应聘状况等信息进行查询，也是为了更好的让管理员进行更好存储所有数据信息及快速方便的检索功能，对系统的各个模块是通过许多今天的发达系统做出合理的分析来确定考虑用户的可操作性，遵循开发的系统优化的原则，经过全面的调查和研究。

系统所要实现的功能分析，对于现在网络方便的管理，根据自己的需求可以进行查看信息等，这样既能节省用户的时间，不用在像传统的方式，需要查询、由于很多用户时间的原因，没有办法去了解，真的很难去满足用户的各种需求。所以人职匹配推荐系统的开发不仅仅是能满足用户的需求，还能提高管理员的工作效率，减少原有不必要的工作量。
## 3.2 系统可行性分析
系统的开发环境和配置都是可以自行安装的，系统使用Java开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台之间相关的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得系统运行更具有稳定性和安全性，从而完成实现系统的开发。

硬件可行性分析

人职匹配推荐系统及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开系统必须顺畅，不能停顿太长时间；性价比高；安全性高。

因此，我们从这个方面进行了可行性研究，可以看出系统的开发没有问题。
## 3.3 系统功能分析和描述
使用人职匹配推荐系统分为管理员和用户、企业三个权限子模块。

管理员所能使用的功能主要有：首页、个人中心、用户管理、企业管理、岗位信息管理、岗位类型管理、应聘信息管理、应聘状况管理、平台费用管理、系统管理等。

用户可以实现；首页、个人中心、应聘信息管理、应聘状况管理、我的收藏管理等。

企业可以实现；首页、个人中心、岗位信息管理、应聘信息管理、应聘状况管理、平台费用管理等。

## 3.4系统UML用例分析
### 3.4.1管理员用例
管理员登录后可进行首页、个人中心、用户管理、企业管理、岗位信息管理、岗位类型管理、应聘信息管理、应聘状况管理、平台费用管理、系统管理，管理员的用例如图3-1所示。

![](/md/blog.002.png)

图3-1 管理员用例图
### 3.4.2用户用例
用户注册登录后可进行首页、个人中心、应聘信息管理、应聘状况管理、我的收藏管理，用户用例如图3-2所示。

![](/md/blog.003.png)

图3-2 用户用例图
## 3.5系统流程分析
### 3.5.1添加信息流程
添加信息,编号系统使用自动编号模式,没有用户填写,用户添加信息输入信息,系统将自动确认的信息和数据,验证的成功是有效的信息添加到数据库,信息无效,重新输入信息。添加信息流程如图3-3所示。

![](/md/blog.004.png)

图3-3 添加信息流程图
### 3.5.2操作流程
用户想进入系统，首先进入系统登录界面，通过正确的用户名、密码，选择登录类型登录，系统会检查登录信息，信息正确，然后输入相应的功能界面，提示信息错误，登录失败。系统操作流程如图3-4所示。

![](/md/blog.005.png)

图3-4操作流程图
### 3.5.3删除信息流程
用户选择要删除的信息并单击Delete按钮。系统提示是否删除信息。如果用户想要删除信息，系统将删除信息。系统数据库删除信息。删除信息流程图如图3-5所示。

![](/md/blog.006.png)

图3-5 删除信息流程图


# 第四章 系统设计
## 4.1 系统体系结构
人职匹配推荐系统的结构图4-1所示：

网

络

企业

服务器和程序

管理员

用  户

![](/md/blog.007.png)

图4-1  系统结构

模块包括主界面，首页、个人中心、用户管理、企业管理、岗位信息管理、岗位类型管理、应聘信息管理、应聘状况管理、平台费用管理、系统管理等进行相应的操作。

登录系统结构图，如图4-2所示：

Y

人职匹配推荐系统登录界面

用户登录

密码正确

管理员界面

企业界面

用户界面

![](/md/blog.008.png)

图4-2 登录结构图

这些功能可以充分满足人职匹配推荐系统的需求。此系统功能较为全面如下图系统功能结构如图4-3所示。

![](/md/blog.009.png)

图4-3系统功能结构图

## 4.2 数据库设计原则
每个数据库的应用它们都是和区分开的，当运行到一定的程序当中，它就会与自己相关的协议与客户端进行通讯。那么这个系统就会对使这些数据进行连接。当我们选择哪个桥段的时候，接下来就会简单的叙述这个数据库是如何来创建的。当点击完成按钮的时候就会自动在对话框内弹出数据源的名称，在进行点击下一步即可，直接在输入相对应的身份验证和登录密码。 

人职匹配推荐系统的数据流程：

![](/md/blog.010.png)

图4-4  系统数据流程图

企业信息实体E-R图，如图4.5所示。

![](/md/blog.011.png)

`    `图4.5企业信息E-R图

平台费用信息E-R图，如图4.6所示。

![](/md/blog.012.png)

` `图4.6平台费用信息E-R图

## 4.3 数据表
将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。
#########
表4-1 allusers表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|username|varchar|50|` `default NULL|
|pwd|varchar|50|` `default NULL|
|cx|varchar|50|` `default NULL|


表4-2 pingtaifeiyong表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|feiyongbianhao|varchar|50|default NULL|
|nianyue|varchar|50|default NULL|
|feiyongleixing|varchar|50|default NULL|
|feiyongjine|varchar|50|default NULL|
|qiyezhanghao|varchar|50|default NULL|
|qiyemingcheng|varchar|50|default NULL|
|fuzeren|varchar|50|default NULL|
|lianxifangshi|varchar|50|default NULL|

表4-3：qiye表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|qiyezhanghao|varchar|50|default NULL|
|mima|varchar|50|default NULL|
|qiyemingcheng|varchar|50|default NULL|
|qiyedizhi|varchar|50|default NULL|
|qiyeguimo|varchar|50|default NULL|
|fuzeren|varchar|50|default NULL|
|lianxifangshi|varchar|50|default NULL|
|qiyetupian|varchar|50|default NULL|
|qiyeyouxiang|varchar|50|default NULL|
|qiyejianjie|varchar|50|default NULL|


表4-4：yingpinzhuangkuang表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|zhiweimingcheng|varchar|50|default NULL|
|gangweileixing|varchar|50|default NULL|
|qiyezhanghao|varchar|50|default NULL|
|qiyemingcheng|varchar|50|default NULL|
|fuzeren|varchar|50|default NULL|
|lianxifangshi|varchar|50|default NULL|
|yonghuzhanghao|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|yonghushouji|varchar|50|default NULL|
|zhuangtai|varchar|50|default NULL|
|neirong|varchar|50|default NULL|
|gengxinshijian|varchar|50|default NULL|


表4-5：yonghu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|yonghuzhanghao|varchar|50|default NULL|
|mima|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|xingbie|varchar|50|default NULL|
|nianling|varchar|50|default NULL|
|touxiang|varchar|50|default NULL|
|touxiang|varchar|50|default NULL|
|biyeyuanxiao|varchar|50|default NULL|
|zuigaoxueli|varchar|50|default NULL|
|qiwangzhiwei|varchar|50|default NULL|
|xinziyaoqiu|varchar|50|default NULL|
|qiwangchengshi|varchar|50|default NULL|



# `    `第五章 系统实现
## 5.1用户功能模块
用户点击进入到系统操作界面，可以对首页、个人中心、应聘信息管理、应聘状况管理、我的收藏管理等功能模块，应聘信息管理：通过列表可以获取职位名称、岗位类型、企业账号、企业名称、负责人、联系方式、用户账号、姓名、用户手机、性别、年龄、毕业院校、最高学历、个人简历并进行修改操作，如图5-1所示。

![](/md/blog.013.png)

图5-1应聘信息管理界面图

应聘状况管理：通过列表可以获取职位名称、岗位类型、企业账号、企业名称、负责人、联系方式、用户账号、姓名、用户手机、状态、内容、更新时间等信息，进行详情、修改、删除操作，如图5-2所示。

![](/md/blog.014.png)

图5-2应聘状况管理界面图



## 5.2管理员功能模块
管理员通过用户名和密码、角色填写完成后进行登录，如图5-3所示。管理员登录成功后进入到系统操作界面，可以对首页、个人中心、用户管理、企业管理、岗位信息管理、岗位类型管理、应聘信息管理、应聘状况管理、平台费用管理、系统管理等功能模块进行相对应操作。

用户管理：通过列表可以获取用户账号、姓名、性别、年龄、头像、用户手机、毕业院校、最高学历、期望职位、薪资要求、期望城市等内容，可以进行修改或删除操作，如图5-4所示。

![](/md/blog.015.png)

图5-3管理员登录页面

![](/md/blog.016.png)

图5-4用户管理页面

企业管理：通过列表可以获取企业账号、企业名称、企业地址、企业规模、负责人、联系方式、企业图片、企业邮箱等信息，进行删除或修改操作，如图5-5所示。


![](/md/blog.017.png)

图5-5企业管理界面图

岗位类型管理：通过列表可以获取岗位类型等信息，进行修改或删除操作，如图5-6所示。

![](/md/blog.018.png)

图5-6岗位类型管理界面图 

应聘信息管理：通过列表可以获取职位名称、岗位类型、企业账号、企业名称、负责人、联系方式、用户账号、姓名、用户手机、性别、年龄、毕业院校、最高学历、个人简历等信息，进行修改或删除操作，如图5-7所示。

![](/md/blog.019.png)

图5-7应聘信息管理界面图

应聘状况管理：管理员通过列表可以获取职位名称、岗位类型、企业账号、企业名称、负责人、联系方式、用户账号、姓名、用户手机、状态、内容、更新时间等信息，进行修改或删除操作，如图5-8所示。

![](/md/blog.020.png)

图5-8应聘状况管理界面图

平台费用管理：管理员通过列表可以获取费用编号、年月、费用类型、费用金额、企业账号、企业名称、负责人、联系方式、是否支付等信息，进行修改或删除操作，如图5-9所示。

![](/md/blog.021.png)

图5-9平台费用管理界面图

## 5.3企业功能模块
企业点击进入到系统操作界面，可以对首页、个人中心、岗位信息管理、应聘信息管理、应聘状况管理、平台费用管理等功能模块，个人信息：通过列表可以获取企业账号、企业名称、企业地址、企业规模、负责人、联系方式、企业图片、企业邮箱并进行修改操作，如图5-10所示。

![](/md/blog.022.png)

图5-10个人信息界面图

平台费用管理：通过列表可以获取费用编号、年月、费用类型、费用金额、企业账号、企业名称、负责人、联系方式、是否支付等信息，进行详情、修改、删除操作，如图5-11所示。

![](/md/blog.023.png)

图5-11平台费用管理界面图

应聘信息管理：通过列表可以获取职位名称、岗位类型、企业账号、企业名称、负责人、联系方式、用户账号、姓名、用户手机、性别、年龄、毕业院校、最高学历、个人简历等信息，进行详情、修改、删除操作，如图5-12所示。

![](/md/blog.024.png)

图5-12应聘信息管理界面图

应聘状况管理：通过列表可以获取职位名称、岗位类型、企业账号、企业名称、负责人、联系方式、用户账号、姓名、用户手机、状态、内容、更新时间等信息，进行详情、修改、删除操作，如图5-13所示。

![](/md/blog.025.png)

图5-13应聘状况管理界面图







## 5.4前台首页功能模块
人职匹配推荐系统，在系统首页可以查看首页、企业、岗位信息、新闻资讯、个人中心、后台管理等内容，如图5-14所示。

![](/md/blog.026.png)

图5-14前台首页功能界面图



`    `用户注册，在注册页面可以填写用户账号、密码、姓名、性别、用户手机、毕业院校、最高学历、期望职位、薪资要求、期望城市等信息进行注册，如图5-15所示。

![](/md/blog.027.png)

图5-15用户注册界面图
#########
用户登录，在登录页面通过填写账号、密码等信息完成登录，如图5-16所示。在应聘信息页面通过查看职位名称、岗位类型、企业账号、企业名称、负责人、联系方式、用户账号、姓名、用户手机、性别、年龄、毕业院校、最高学历、个人简历等信息进行提交操作，如图5-17所示。

![](/md/blog.028.png)

图5-16用户登录界面图
#########
![](/md/blog.029.png)

图5-17应聘信息界面图












