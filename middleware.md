[TOC]
# 1、Redis
1. Redis的数据类型有几种？
五种，分别是List，String，Set，SortSet，Hash。

2、有了解过memcache吗？它和Redis的区别在哪？
* memcache只能存储KV结构的数据或音像文件，Redis除了KV数据还有上面说的五种可以存；
* memcache必须设置数据的过期时间，但Redis对数据的过期时间不强制要求设置；
* 在容灾上memcache的数据丢了就没了，Redis可以主从复制
* Redis可以持久化数据到本地文件里

# 2、kafka

# 3、elasticsearch

# Linux
1. 系统报错，你是怎么查日志进行排查，能举例说明吗？
Linux系统下查询日志有tail查询实时日志，sed根据时间筛选日志。

