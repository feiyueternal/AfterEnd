# AfterEnd

> 均采用面向对象形式

都采用面向对象的方法，不要直接写方法

> 接口思想编程

不要把真正实现的代码暴露成api，采用接口调用的形式（我在java上是这样做的，python上应该有类似的思想）；impl的package存放的是实现的类

> 项目结构

1.model: 数据库对象

2.untils: 工具类，数据流转文件存储、图片url地址设置

3.service: 业务逻辑