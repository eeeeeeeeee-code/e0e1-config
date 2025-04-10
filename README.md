﻿# e0e1-config

## 功能简介
  该工具主要用于后渗透方面，包含：
  1. Windows记事本和Notepad++ 保存与未保存内容提取
  2. 向日葵  获取id、密码、配置信息
  3. ToDesk  获取id、密码、配置信息
  4. Navicat  获取数据库连接信息
  5. DBeaver  获取数据库连接信息
  6. FinalShell  获取连接信息
  7. Xshell和Xftp  获取连接信息
  8. FileZilla  获取连接信息
  9. winscp  获取连接信息
  10. 敏感信息文件搜索

## 工具使用示例
> 编译
> go build -ldflags "-w -s" ./

> 参数示例
>   e0e1-config -winscp   #获取winscp连接信息，通过默认配置文件和注册表
> 
>   e0e1-config -winscp -winscp-path "C:\path\winscp.ini"  #自定义配置文件路径
> 
>   e0e1-config -all      #执行所有功能
> 
>   e0e1-config -all -output "result.txt"   #执行所有功能，并将输出 输入到result.txt文件中
> 
