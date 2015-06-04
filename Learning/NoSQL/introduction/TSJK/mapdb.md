#图数据库
##图数据库定义
图数据库可存放实体及实体间关系。实体为“节点”，关系为“边”，边具备方向性。

几种图数据库：

* Neo4J
* Infinite Graph
* OrientDB
* FlockDB

图数据库的好处有：

* 无需改变节点或边，即可应对心的遍历需求。

* 图数据库遍历“连接”及“关系”非常快。节点间的关系不在查询映射计算，而是在创建时已经持久化了。遍历持久化之后的关系，要比每次查询时都计算关系更快。