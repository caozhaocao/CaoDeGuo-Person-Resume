# 基本信息 #

  曹德国    深圳
  
  江西理工大学 本科（2009--2013）
  
  地理信息系统（GIS）
  
  13133974252
  
  13133974252@163.com


# 自我评价 # 
1. 项目开发中一般会编写 需求文档、开发文档、帮助文档 等各种报告文档；
2. 熟悉应用数据结构和算法，让程序的时间复杂度最小，提高程序的运行速度；
3. 技术栈主要是.Net和Python，偏向于后台开发；
4. 会应用设计模式，会周期性的重构代码，会定期的优化程序；
5. 能够与同事一起协作,也可以带领同事一起做项目；
6. 喜欢折腾技术、有轻度强迫症。  


# 工作经历 #
2019.03 — 现在  深圳市法本信息技术股份有限公司  
**职位：** C#、DevOps工程师  
IT服务（开发）| 企业性质：私企 | 规模：7000人  
**所在部门：** 项目开发部  
**所做项目：** 格力自动化管理项目、首汽约车出租车平台  

2016.07 — 2018.08  软通动力信息技术有限公司  
**职位：** 技术经理、算法应用工程师  
IT服务（开发）| 企业性质：上市公司 | 规模：1万人  
**所在部门：** 华为GTS实施部  
**所做项目：** 德电KPI、传播模型校正、多频段算法  

2014.03 — 2016.05  富智康实验室 (富士康)  
**职位：** C#工程师  
生产企业 | 企业性质：上市公司 | 规模：1百万人以上  
**所在部门：** 实验室研发部  
**所做项目：** 电商资料管理系统、手机性价比工具、检测工业互联网大数据分析  


# 项目经验 #

### 项目一：格力自动化管理项目  
**时间：** 2019.6 — 2019.12  
**所用技术：**  Devops/ Java/Vue  
**项目描述：**  
1.设备动力部作为管理单位可查看所有单位的单据和数据，其他单位间数据互相隔离。  
2.可进行用户授权和新增删除功能，可进行项目的负责进行更换操作等。    
**完成任务：**    
1.Jenkins使用Git和Maven工具CICD；  
2.Docker快速部署开发软件。  
**关键点：**  
1.引进在Linux下Devops的自动化CICD技术，随时发布；  
2.引进敏捷开发。  
**结果：**  
1.使用CICD（持续集成，部署，发布），提高了开发和运维的效率，让一周发布一次到一天可以发布100次；  
2.引进敏捷开发，使用MVP方法低成本的尝试，以及快速响应需求的变更。  


### 项目二：首汽约车出租车平台  
**时间：** 2019.3 — 2019.6  
**所用技术：** C# /H5  
**项目描述：**    
基于网约车平台，开放给企业员工用车，员工基于H5叫车，为企业员工新添一个约车供应商，企业员工选择网约车平台，用车费用由企业和该网约车平台结算，无须员工支付。  
**完成任务：**   
新增了网约车的员工新入口，方便客户使用H5约车。  
**关键点：**  
1.使用WCF让框架腾讯地图的map_api.js、Web层与中间层进行交互；  
2.为了提高系统性能，前端静态资源使用了腾讯云CDN进行加速；   
3.管理后台用的是ASP.NET MVC技术给前端提供接口。  
**结果：**  
如期完成了该期（第二期）的需求，交付给了客户测试，压力测试达到了TPS=100以上。  


### 项目三： 智能物流 
**时间：** 2018.04 — 2018.08  
**所用技术：** C#  
**项目描述：**  
智能物流，为无人工厂也为自动化工厂 的一个材料运输环节，目前处在 半自动化工厂的协作方式，因为很多方面的不够完善，需要 人工进行协作，正在向 自动化工厂过渡。  
**智能物流主要包括：**    
软件部分：LCTS（物流调度系统）、IMS（动态物料系统）、WCS（物联网通讯系统）、OPC（接驳台控制系统）、EMCS（产线单元系统）  
硬件部分：AGV（自动导引运输车）  
负责的模块：LCTS-物流调度系统,大体原理为:根据IMS发出的物料运输指令，通过WCS通知AGV进行物料的运送和上下料的动作，并且对AGV进行路线规划和实现 并对多个AGV的交通规则进行设计和实现。  
**完成任务：**    
1.在电镀上 同时容纳3个AGV车不让发生碰撞的交通规则，让AGV高效率的完成运输任务；  
2.AGV在低电压的情况下先去充电桩自动充电，然后接受运输任务。  
**关键点：**  
1.WCS（物联网通讯系统）让设备间保持联络畅通，保持一定量的并发；  
2.优化路径的算法，在主干道上有交通管制的地方，既不让AGV车发生蓬窗，也让AGV车少停止。  
**结果：**  
1.AGV车在主干道上少了碰撞和停止不动的情况；  
2.AGV车在空闲时少于一定电压时，会去充电桩充电。  

### 项目四： 传播模型校正    
**时间：** 2016.8 — 2017.10  
**所用技术：** C#/Java  
**项目描述：**   
在CBB平台的应用程序中添加周边站点校正模型，与原有的邻区校正模型可以任意的切换选择。  
1.原有的邻区校正模型不能精确的反应各项数据，所以添加周边站点校正模型；  
2.一线人员和测试人员可以根据不同的场景进行选择不同的校正模型获取精准的数据。  
**完成任务：**    
了解客户的需求后，调整算法模型，让一线使用者可以按照不同场景，切换不同的模型。  
**关键点：**  
1.独立完成原有的邻区校正模型程序中加入周边站点校正模型，并在XML中做成开关可以切换；  
2.二套校正模型 输出的log日志与预期的保持一致，并做好代码的单元测试。  
**结果：**  
算法程序优化后，客户比较满意，之后与一线人员直接联系，一线人员把疑问和业务需求提前跟我们沟通。  


### 项目五：检测工业互联网大数据分析  
**时间：** 2015.10 — 2016.3  
**所用技术：** C#  
**项目描述：**  
检测工业互联网大数据分析 在确保安全保密，设定对数据的分级权限设置，使用Hadoop系统建立数据存储、处理、分析、统计、安全一整套的应用平台。  
1.与南方检测、FTC实验室、ECME、CMMSG EC部门合作;    
2.对现有手机的结构化的数据(包括硬件测试数据，应用软件APP测试数据，销售数据)进行分布式的储存和清洗，转换，处理和分析，知识表达，以可视化的形式反馈给各部门;  
3.计划后续数据延伸到文档，视频，语音。  
**完成任务：**    
1.初步规划实验室测试数据挖掘的方向报告和分配作业任务；  
2.完成在Azure平台创建虚拟机并搭建Hadoop和HBase框架。  
**关键点：**  
1.联合南方检测、FTC实验室、ECME、CMMSG EC部门，把各部门手机的各项测试数据收集起来（数据包括数据库和excel数据，之后会有文档，视频，语音）；  
2.用Hadoop做大数据平台，用HBase作储存的数据库，MapReduce做大数据的处理模型。  
**结果：**  
完成了前期Hadoop实施的报告，并把该项目移交到富士康河北廊坊大数据部门。  

### 项目六：手机性价比工具  
**时间：** 2015.4 — 2015.7  
**所用技术：** C#（WinForm、WinWeb）  
**项目描述：**  
应产品部门的要求，设计手机性价比的排名工具。  
1.做一款类似安兔兔、360跑分王、鲁大师的手机性价比的排名工具。  
2.由于对硬件不熟悉，所以对其手机零部件需要手动打分和加权。  
**完成任务：**    
1.协助产品部门完成需求分析，完成UML；  
2.独自完成所有任务的开发和单元测试;  
3.撰写手机性价比报告和开发文档;  
4.发布和上线新版本。  
**关键点：**  
1.各项可视化图像的绘制；  
2.把WinForm桌面版迁移到WinWeb网页版。  
**结果：**  
1.独自完成WinForm版的手机性价比工具，供部门人员使用；  
2.带领四位同事完成WinWeb版的手机性价比工具，供产品和其它部门使用。  
