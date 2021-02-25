# niubade_im_ReverseEngineering

#### 介绍
**此项目为niubaide_im配套逆向工程**  
niubaide_im为一个即时通讯系统  
此逆向工程为该工程下的逆向工程  
主要用于生成Java pojo对象，mapper接口文件与接口映射文件

#### 软件架构
主要使用`mybatis-generator-core`核心jar包  
配置文件为`generatorConfig.xml`，其中注释已经注明  
有问题请提issues，有问题我会看


#### 安装教程

1.  `git clone https://github.com/loks666/niubade_im_ReverseEngineering.git`  
2.  .idea文件夹已忽略提交，所以需要重新配置数据库地址、账号密码以及JDK和Maven资源路径
3.  在数据库执行`src/main/resources/nchat.sql`文件，生成相关的数据库表及测试数据    
3.  运行`GeneratorSqlmap`下的`main`方法即可
4.  生成文件路径在`generatorConfig.xml`中配置，其中绝对路径与相对路径亲测都可

------
- github 主页 [https://github.com/loks666/niubaide_im](https://github.com/loks666/niubaide_im)  
- gitee 主页 [https://gitee.com/lok666/niubaide_im](https://gitee.com/lok666/niubaide_im)  

