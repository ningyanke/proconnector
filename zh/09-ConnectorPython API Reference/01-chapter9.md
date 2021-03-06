﻿9.1 模块 mysql.connector
===========================

mysql.connector模块提供top-level方法和属性。

## 9.1.1 方法 mysql.connector.connect()

该方法设置一个连接，建立与Mysql的会话。如果没有给定参数，它将使用已配置的或者默认值。完整的可用参数列表见[第7章 Connector/Python 连接参数](../07-ConnectorPython Connection Arguments/00-chapter7.md)。
	
与Mysql服务器的连接可以通过mysql.connector.connect()方法或者mysql.connector.MySQLConnection()类建立。

```python

	 cnx = mysql.connector.connect(user='joe',database='test')cnx = MySQLConnect(user='joe',database='test')
```

## 9.1.2 属性 mysql.connector.apilevel

该属性是一个字符串，表明支持的DB API级别。

## 9.1.3 属性 mysql.connector.paramstyle

该属性是一个字符串，表明Connector/Python默认参数样式。

## 9.1.4 属性 mysql.connector.threadsafety

该属性是一个整数，表明Connector/Python提供的线程安全支持的级别。

## 9.1.5 属性 mysql.connector.\__version\__

该属性是一个字符串，表明Connector/Python版本。

## 9.1.6 属性 mysql.connector.\__version_info\__

该属性以版本组件数组的形式表明Connector/Python的版本。