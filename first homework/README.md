##红岩网校暑期培训第一次课件

###主要内容

多态
抽象类&&接口
内部类
java基础数据结构
适配器模式&&工厂模式
###作业

学习以上两个模式，并照自己的理解写出相应的例子（下节课每个人一一叙述）
实现 Readable 接口，并使用Scanner扫描它，体会接口的优势
用java链接数据库，并尝试增删改查数据
搭建自己的服务器（主要是运行环境的搭建），不会的使用 https://natapp.cn/ 尝试使用内网穿透把自己的电脑当作服务器，然后申请微信公众测试账号，让服务器接入微信，具体过程见微信开发者文档
###java se7中文文档Dash版

链接: https://pan.baidu.com/s/1cCRlWa 密码: n325





第一个--适配器模式：

1.概述

将一个类的接口转换成客户希望的另外一个接口。Adapter模式使得原本由于接口不兼容而不能一起工作的那些类可以在一起工作。

2.解决的问题

即Adapter模式使得原本由于接口不兼容而不能一起工作的那些类可以在一起工作。

3.实现方式

类的适配器模式（采用继承实现）

对象适配器（采用对象组合方式实现）

↑这个没写到代码里    大概就是委托方式 ↓

（private Adaptee adaptee; 直接关联 然后通过构造函数直接获取传入的adaptee类  --------然后 this.adaptee = adaptee; 保存  通过this.adaptee.specificRequest();  调用）

还是拿动物说   emmm 放在Adapter里





第二个 -- 工厂模式

=、= 就写简单工厂...

在Factory里 (emmmm 还是food讲过的好写...)



第三个 -- readable 

emmmmm 还没成...
