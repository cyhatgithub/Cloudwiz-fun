# **UI界面 - 系统总览**

系统总览提供了对被监控系统节点的总体状况的概览。

## 1.**高管驾驶舱**

高管驾驶舱概述当前不同系统的状态![](/part4/images/p4_2.png)

## 2.**系统总览**
系统总览页面展示反应当前系统健康状况的关键指标信息

![](/part4/images/summary_service.png)


### 2.1 创建服务依赖
> 创建服务依赖入口修改至 monitoring>>resources>>create topology

![](/part4/images/service_dep.png)

### 2.2 资源状态

入口为monitoring>>resources，此视图列出了所有被监控的资源，每种资源用不同的图标显示，颜色则代表了其当前的状态，其中绿色为正常状态，黄色为警告状态，红色则为异常状态，状态值的计算同时考虑了Azure资源本身的状态以及资源告警情况。

![](/part4/images/host_topology.png)

可以通过上方的搜索框针对资源名称进行搜索，或使用下拉框针对资源组或状态进行过滤。

点击任意资源图标，即可查看资源的详细信息，包括Azure属性、当前告警状况等。对于包含指标的资源，如Web App、SQL Server、SQL Database、Redis Cache、Storage、Scheduler等，可以查看相关指标的趋势。

![]()
