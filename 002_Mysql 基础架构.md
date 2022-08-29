##  Mysql 基础架构

Mysql 分为服务层和存储引擎层：

- 服务层：
  - 连接器
  - 查询缓存
  - 分析器
  - 优化器
  - 执行器
- 存储引擎层：默认的是 InnoDB
  - InnoDB
  - MyISAM
  - ...

![MysqlArch](.\images\MysqlArch.png)