# redis（非关系性数据库）

- 单线程 + 多路IO复用  
<br>
- 常用五大数据类型
> 字符串（string）  
> 列表（list）  
> 集合（set）  
> 哈希（Hash）  
> 有序集合（Zest）

- 哪里去获得 redis 常见数据类型操作命令  
[http://www.redis.cn/commands.html](http://www.redis.cn/commands.html)



<br><br><br>
> 额外收获  
>- MAC的docker安装的redis怎么通过终端连接redis  
> 命令: docker exec -ti 960283ddba38(运行的容器名，docker ps查看) redis-cli  
>- 终端命令敲太多想清掉  
> 方法： 直接clear命令 (举例：<127.0.0.1:6379> clear) 