# 目录

# 简介

- [什么是CeresDB](about.md)
- [快速开始](quick_start.md)

# 用户手册

- [SQL语法](sql/README.md)
    - [数据模型](sql/model/README.md)
        - [数据类型](sql/model/data_types.md)
        - [特殊字段](sql/model/special_columns.md)
    - [标识符](sql/identifier.md)
    - [表结构操作](sql/ddl/README.md)
        - [建表](sql/ddl/create_table.md)
        - [变更表结构](sql/ddl/alter_table.md)
    - [数据操作](sql/dml/README.md)
        - [插入数据](sql/dml/insert.md)
        - [查询语句](sql/dml/select.md)
    - [工具SQL](sql/utility.md)
    - [引擎参数](sql/engine_options.md)

- [部署文档](deploy/README.md)
    - [支持平台](deploy/platform.md)
    - [静态路由](deploy/static_routing.md)
    - [动态路由](deploy/dynamic_routing.md)

- [SDK文档](sdk.md)
    - [Java SDK](sdk/java.md)
    - [Go SDK](sdk/go.md)
    - [Python SDK](sdk/python.md)
    - [Rust SDK](sdk/rust.md)
  
- [运维文档](operation/README.md)
    - [Table](operation/table.md)
    - [System Table](operation/system_table.md)
    - [黑名单](operation/block_list.md)
    - [监控](operation/observability.md)

# 开发指南
- [支持平台](dev/platform.md)
- [编译运行](dev/compile_run.md)
- [开发规约](dev/conventional_commit.md)
- [风格规范](dev/style_guide.md)
- [里程碑](dev/roadmap.md)

# 技术系列文章
- [整体架构](architecture.md)
- [存储介绍](storage.md)
- [查询介绍](query.md)
- [Wal介绍](wal.md)
- [表分区](table_partitioning.md)

