第一章 介绍
===============
MySQL Connector/Python 使得Python程序能通过使用兼容[Python Database API Specification v2.0(PEP 249)](http://legacy.python.org/dev/peps/pep-0249/)的API访问MySQL数据库。它完全是纯Python和除[Python Standard Library](https://docs.python.org/2/library/)外没有其他依赖。

对于每个Connector/Python版本变化的细节，请查看[MySQL Connector/Python Release Notes](http://dev.mysql.com/doc/relnotes/connector-python/en/)

MySQL Connector/Python 有如下支持：

- 几乎支持MySQL服务器版本5.5及以上的所有特征。
- Python和MySQL数据类型的相互转换，例如，Python的datetime和MySQL的DATETIME。为了方便你可以开启自动转换，或者为了性能关闭自动转换。
- 所有标准SQL语法的MySQL扩展。
- 协议压缩，开启压缩客户端和服务器端间的数据流。
- 使用TCP/IP sockets连接和在UNIX上使用unix sockets连接。
- 使用SSL进行安全的TCP/IP连接。
- 自包含驱动。Connector/Python不要求MySQL客户端库或者任何Python标准库以外的其他库。

MySQL Connector/Python 1.1支持的Python版本从2.6到2.7，Python 3.1及更新版本。
MySQL Connector/Python 1.0支持的Python版本从2.4到2.7，Python 3.1及更新版本。

注意：Connector/Python 不支持旧的MySQL服务器的认证方法，这意味着MySQL 4.1之前的版本无法正常工作。