Spark升级
1）部署包的升级
    a: 下载对应需要的Spark源码包
    b: 解压源码包
    c: 编译
    d: 解压安装包到~/app
    e: 配置环境变量SPARK_HOME

PS:
    a：Spark on YARN，只需要在你的提交机器上部署编译后的Spark安装包即可
    b：Spark on Standalone，你的Spark集群中的每个机器都需要部署编译后的Spark安装包

2）代码的升级
    a: 升级所需要的Spark对应的版本
        <spark.version>2.4.2</spark.version>
    b: 在dependency中修改sql和streaming依赖的Spark版本




Window API

csv：以前的Spark版本来说，是需要通过第三方实现的外部数据源来操作
    Build-in


Spark SQL：coalesce repartition
HINT:
    Hive早期时，MapJoin   /*+ a*/



Spark SQL中的Catalog












