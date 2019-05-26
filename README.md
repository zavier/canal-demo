# 配置

## 1.数据库开启binlog

vim /etc/my.cnf
添加
```bash
log-bin=mysql-bin
binlog-format=ROW
server_id=1
```

## 2.QuickStart启动

[参考文档](https://github.com/alibaba/canal/wiki/QuickStart)

可能遇到的问题，java.net.UnknownHostException

解决方式：vim /etc/hosts

添加:
`127.0.0.1   [主机名]   localhost`

## 3.创建项目
