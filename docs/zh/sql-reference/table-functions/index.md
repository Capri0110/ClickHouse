---
machine_translated: true
machine_translated_rev: 72537a2d527c63c07aa5d2361a8829f3895cf2bd
toc_folder_title: "\u8868\u51FD\u6570"
toc_priority: 34
toc_title: "\u5BFC\u8A00"
---

# 表函数 {#table-functions}

表函数是构造表的方法。

您可以使用表函数:

-   [FROM](../statements/select/from.md) 语句， 在使用 `SELECT` 查询时。

        使用临时表的方法只对当前查询有效，表会在完成查询后自动删除。

-   [CREATE TABLE AS\<table\_function()\>](../statements/create.md#create-table-query) 查询。

        一个创建表的标准方法

!!! warning "警告"
    如果 [allow\_ddl](../../operations/settings/permissions-for-queries.md#settings_allow_ddl) 设置被禁用，你将不能使用表函数。

| 功能               | 产品描述                                                                                               |
|--------------------|--------------------------------------------------------------------------------------------------------|
| [文件](file.md)    | 创建一个 [File](../../engines/table-engines/special/file.md)-引擎表。                                |
| [合并](merge.md)   | 创建一个 [Merge](../../engines/table-engines/special/merge.md)-引擎表。                               |
| [数字](numbers.md) | 创建一个包含整数的单列表。                                                                       |
| [远程](remote.md)  | 允许您在无需创建 [Distributed](../../engines/table-engines/special/distributed.md)-引擎表时访问远程服务器。 |
| [url](url.md)      | 创建一个 [Url](../../engines/table-engines/special/url.md)-发动机表。                                  |
| [mysql](mysql.md)  | 创建一个 [MySQL](../../engines/table-engines/integrations/mysql.md)-引擎表。                         |
| [jdbc](jdbc.md)    | 创建一个 [JDBC](../../engines/table-engines/integrations/jdbc.md)-引擎表。                           |
| [odbc](odbc.md)    | 创建一个 [ODBC](../../engines/table-engines/integrations/odbc.md)-引擎表。                           |
| [hdfs](hdfs.md)    | 创建一个 [HDFS](../../engines/table-engines/integrations/hdfs.md)-引擎表。                           |

[原始文章](https://clickhouse.tech/docs/en/query_language/table_functions/) <!--hide-->
