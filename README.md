# sqoop2
> 通过maven构建的scala程序

### 介绍
> 5个oralce数据库的表，大约3000张表，同步到doris(原palo)
1. 通过脚本sql在源库执行，把创建job的参数拼接查询出来，后面会提供出sql脚本
2. 查询出来的参数有,OWNER,TABLE_NAME,SELECT SQL,数据行数
