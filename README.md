spring-boot学习，实验1
实验目的
掌握基于idea的基本springboot工程项目的创建方法。
理解maven项目结构，依赖配置声明管理。
掌握DO类与数据表的映射规则。    
掌握基本的属性映射规则。
理解雪花算法主键生成策略与特点。
掌握基于spring-data-jdbc框架的基本CURD操作。

实验内容
创建springboot项目，添加spring-data-jdbc框架相关依赖。
创建springboot项目配置文件，添加数据源/logging等相关配置。
创建数据表生成脚本，编写user表结构。
打开idea database视图，添加连接远程数据库。
执行脚本生成测试数据表。
编写user表对应的DO类，按映射规则声明属性。
编写雪花算法注入实现。
编写操作DO类的Repository组件。
编写测试类，注入Repository组件，执行增删改等持久化方法。
测试事务
