# 1. 项目启动

1.1 数据库启动、连接

    - 打开cmd，以管理员身份运行
    - 执行命令 net start MySQL80 
        
1.2 Redis启动、连接

    - 打开目录 D:\software\Redis-x64-3.2.100, 开启Cmder终端
    - 执行指令 
        .\redis-cli.exe
        shutdown
        exit
        .\redis-server.exe

1.3 Elasticsearch启动、连接
    
    - 打开目录 D:\software\elasticsearch-7.6.1\bin, 开启Cmder终端
    - 执行指令 
        .\elasticsearch.bat
    
1.4 Kafka启动、连接

    - 打开目录 D:\software\kafka_2.12-2.3.0\bin\windows, 开启Cmder终端
    - 执行指令 
        zookeeper-server-start.bat ../../config/zookeeper.properties
        kafka-server-start.bat ../../config/server.properties 
    
# 2. 软件安装

2.1 wkhtmltopdf安装
    
    下载： https://wkhtmltopdf.org/downloads.html
    
    refer:  https://blog.csdn.net/weixin_37841366/article/details/109713828
            https://blog.csdn.net/xiaoshuzi666/article/details/108141785
            
            
            
# 3. 错误及解决方案

3.1 git push origin master 提示输入用户名和密码
    
    refer: https://blog.csdn.net/qq_34817440/article/details/102964566    
    
    步骤：
        git remote rm origin
        git remote -v
 
 
 
 
 
 
 
C:\ProgramData\MySQL\MySQL Server 8.0 # my.ini      