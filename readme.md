springboot+mybatis 不用mapper.xml的例子：

导入到项目中:
调整application.yml中数据库地址和帐号密码
运行init.sql创建表
maven构建完成后，启动AccessingDataMysqlApplication.java

测试:
http://localhost:8080/show

查询：
http://localhost:8080/showDao?age=30

插入:
http://localhost:8080/insert?name=chushiyun&age=20
http://localhost:8080/insert?name=guanyu&age=30