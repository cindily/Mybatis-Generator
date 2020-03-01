# Mybatis-Generator

用于快速生成项目中对应数据库表的pojo类

# 使用教程

①使用git clone 命令克隆项目到本地或则直接下载Zip文件到本地再导入IDEA

②修改pom.xml文档中的数据库连接器的配置
项目中使用的是8.0.19版本的mysql，假如不是该版本的数据库需要更改该配置

![image](https://github.com/cindily/Mybatis-Generator/blob/master/MybatisDataGenerator/picture/1.png)

③在dataSource.properties配置文件中修改自己数据库配置
![image](https://github.com/cindily/Mybatis-Generator/blob/master/MybatisDataGenerator/picture/2.png)

④在generatorConfig.xml文件中修改生成的实体的存放包路径
![image](https://github.com/cindily/Mybatis-Generator/blob/master/MybatisDataGenerator/picture/3.png)

⑤在generatorConfig.xml文件中修改生成的*Mapper.java存放路径
![image](https://github.com/cindily/Mybatis-Generator/blob/master/MybatisDataGenerator/picture/4.png)

⑥在generatorConfig.xml文件生成的*Mapper.java存放路径
![image](https://github.com/cindily/Mybatis-Generator/blob/master/MybatisDataGenerator/picture/5.png)

⑦在generatorConfig.xml文件编写数据库中对应的各个表，生成的类名，以及配置自动生成方法有哪些的参数
![image](https://github.com/cindily/Mybatis-Generator/blob/master/MybatisDataGenerator/picture/6.png)

⑧在idea的右方找到maven的标志然后点进去找到plugin的mybatis-generator则会自动执行生成所需文件
![image](https://github.com/cindily/Mybatis-Generator/blob/master/MybatisDataGenerator/picture/0.png)




