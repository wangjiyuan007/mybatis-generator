这是一个为mybatis自动生成pojo、dao接口和映射文件的工具。<br>
使用步骤如下：<br>
1.在pom文件中添加数据库驱动依赖（已经添加了mysql驱动依赖作为示例）<br>
2.更改src/main/resources/generatorConfig.xml中的配置<br>
3.在工程根目录下执行命令:<br>
&nbsp;&nbsp;&nbsp;&nbsp;mvn mybatis-generator:generate