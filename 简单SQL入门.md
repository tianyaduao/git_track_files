## SQL简介
数据库
历史规范
简单组成 select from where
## 使用
安装
ssh连接 xshell secureCRT

### 常用数据库
MySQL
hive

### 数据库建设
建表
    字段，字段类型，表的修改
导数
    分隔符，分区

维度表
事实表
三范式

## 常用SQL
活跃 分城市活跃
新增 
留存率 日对1日 日对7日，7日均值，周对1周
留存的两种存储 放stat_day的分天partition，每天插入到老日期里。或者存储在event_day，可以批量把天数放一个retain partition。

### 聚合运算
sum count group by  having
case when
distinct
join left outer join
union
子查询

### 特殊处理
时间加减，字符串截取合并
hive 窗口函数
模糊匹配 正则表达式
UDF
空值注意 null

## 习题
1，准备好环境，建表，导数，验证
2，活跃计算
3，新增计算
4，留存计算 
2月4号新增 1，在5-11号每天参与活动的人数。2，只在4号参与活动，与在5-11号参与过活动的人数。在5-11号活跃天数分布从0到7
5，聚合运算
6，leetcode SQL题
7，时间加减，字符串截取合并

## 参考
《effective SQL》
## changelog
20190302 初稿


