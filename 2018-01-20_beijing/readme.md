# 首届调度 & 容器技术沙龙上聊了些什么

1 月 20 日，周六，北京，富有历史底蕴的故宫边儿上聚集了这么一批人

![ok7a3906](https://user-images.githubusercontent.com/6755791/35493148-2a447730-04ec-11e8-9b0c-a346c0fac894.JPG)

这次聚会的主题是「调度 & 容器技术」

现场近 300 位 + 线上超过 600 位基础软件技术岗 & 在钻研底层技术的同学在这里共同对调度和容器的实践应用和未来做了的讨论畅想

听起来有点像是改变世界的事情

![ok7a3979](https://user-images.githubusercontent.com/6755791/35493190-7c4ecbac-04ec-11e8-8e89-15020ee04f2d.JPG)

比起改变世界这个笼统的说法，我更希望换成「希望推动行业发展和变革」这样的句子

毕竟，这些人，是认真在研究、做事，然后无私地分享给大家的

这就很有开源的意味了

为了安慰由于地域限制无法到场的报名者，我们在活动前期临时上线了直播服务，全程为大家直播

在这里感谢主办方阿里巴巴系统软件事业部、阿里巴巴技术战略部、ATA 社区、天池直播室

![ok7a4027](https://user-images.githubusercontent.com/6755791/35493255-d54a9600-04ec-11e8-9863-e8bce2f6d301.JPG)

--- 严肃认真的分割线，以下是认真的现场报道 ---

### 第一个话题的 Speaker 是 Kubernetes Maintainer 马达

![ok7a3834](https://user-images.githubusercontent.com/6755791/35493267-e5f1b04c-04ec-11e8-833f-4e0aca97d721.JPG)

<img width="1038" alt="screen shot 2018-01-29 at 12 09 45 pm" src="https://user-images.githubusercontent.com/6755791/35493328-56fb964a-04ed-11e8-9bd8-8d6e987fe4da.png">

他的分享主题是《Kuberentes 中的资源调度与管理》

随着 Kubernetes 的流行，越来越多的作业希望运行在 Kubernetes上，例如 TensorFlow, Spark 等；但目前的 Kubernetes 调度还无法完美支持这些作业模式。在本次讨论中，主要介绍 kubernetes 社区在支持多种作业模式方面所做的工作，并分享这方面的想法及建议。

**Agenda**

1. Kubernetes Overview
2. kube-scheduler overview
3. kube-scheduler overview
4. Priority/Preemption (online service)
5. kube-arbitrator (batch job, offline service)
6. Multi-Scheduler
7. descheduler
8. On-going & Join Community

<img width="883" alt="screen shot 2018-01-29 at 12 12 00 pm" src="https://user-images.githubusercontent.com/6755791/35493374-afa5ec28-04ed-11e8-9089-4bdbf4823e96.png">

⬇️ *点击这里下载讲师 slides*<https://github.com/Lykosteng/schedule-container-meetup/blob/master/2018-01-20_beijing/s%26c_bj_md_kuberentes.pdf>

### 第二个话题的 Speaker 是阿里巴巴天猫双 11 技术大队长叔同

![ok7a3799](https://user-images.githubusercontent.com/6755791/35493482-aab5e910-04ee-11e8-882d-5b0fccd12c9a.JPG)

<img width="1184" alt="screen shot 2018-01-29 at 12 15 28 pm" src="https://user-images.githubusercontent.com/6755791/35493446-3fdc08ae-04ee-11e8-9159-2b0001838d8b.png">

他的分享主题是《阿里巴巴 Sigma 调度 Pouch 容器创新实践》

阿里巴巴的云化技术战略，是阿里基础技术团队近年来一直在努力的方向，是阿里的下一代技术架构。包括混合云、Pouch容器化、Sigma统一调度、存储计算分离和混部等多项技术的不断突破和创新。云化架构使多个数据中心像一台计算机一样来管理，可以跨多个不同的平台来调度业务发展所需的资源，构建混合云以极低成本拿到服务器，通过混合部署大幅提升资源利用率。通过云化架构使双11新增IT成本下降50%，使日常IT成本下降近30%。本分享介绍云化架构关键技术Sigma调度的演进、Pouch容器的路线选择及后续发展规划。

**Aganda**

1. 介绍 Aigma 调度
2. 阿里巴巴混合部署
3. 阿里巴巴开源容器技术 Pouch
4. 未来路线的规划

<img width="1185" alt="screen shot 2018-01-29 at 12 18 10 pm" src="https://user-images.githubusercontent.com/6755791/35494294-a3696a28-04f4-11e8-8e29-3977d73fdd66.png">

<img width="1182" alt="screen shot 2018-01-29 at 12 18 37 pm" src="https://user-images.githubusercontent.com/6755791/35494297-a695aca2-04f4-11e8-8b30-99776db6f0e8.png">

<img width="1181" alt="screen shot 2018-01-29 at 12 18 57 pm" src="https://user-images.githubusercontent.com/6755791/35494299-a7ee5040-04f4-11e8-9ee7-96bf517b69df.png">

<img width="1184" alt="screen shot 2018-01-29 at 12 17 47 pm" src="https://user-images.githubusercontent.com/6755791/35494300-a989f706-04f4-11e8-858f-c3cff9eec164.png">

⬇️ *点击这里下载讲师 slides*<https://github.com/Lykosteng/schedule-container-meetup/blob/master/2018-01-20_beijing/s%26c_bj_st_sigma-pouch.pdf>

### 第三个话题的 Speaker 是搜狗大数据平台资深高级工程师申贤强

![ok7a4137](https://user-images.githubusercontent.com/6755791/35494447-984b42a0-04f5-11e8-828b-a4850e375584.JPG)

<img width="1182" alt="screen shot 2018-01-29 at 1 07 09 pm" src="https://user-images.githubusercontent.com/6755791/35494441-887b41c2-04f5-11e8-92f1-7395b6f572d1.png">

他的分享主题是《DockerOnYarn 调度系统实践》

DockerOnYarn 容器管理系统是大数据平台部自研的微服务容器管理平台，包括编译构建、调度运行、镜像存储等系统工具。结合YARN支持批处理任务与长服务管理，同时支持GPU的板卡隔离和资源调度，目前每天能够稳定调度近30W+的任务/服务。

**Agenda**

1. 背景
2. DockerOnYarn调度实践
  a) Docker在sogou的应用 
  b) DockerOnYarn框架
  c) Docker基础服务优化 
  d) 任务提交与容灾
  e) CIPS-Sogou实践

<img width="1182" alt="screen shot 2018-01-29 at 1 07 56 pm" src="https://user-images.githubusercontent.com/6755791/35494442-88cc1386-04f5-11e8-9425-3fad06cdcc12.png">

<img width="1183" alt="screen shot 2018-01-29 at 1 08 19 pm" src="https://user-images.githubusercontent.com/6755791/35494443-890b28b4-04f5-11e8-8181-ecbba1415b42.png">

⬇️ *点击这里下载讲师 slides*<https://github.com/Lykosteng/schedule-container-meetup/blob/master/2018-01-20_beijing/s%26c_bj_xsq_dockeronyarn.pdf>

### 第四个话题的 Speaker 是灵雀云 k8s 首席专家刘梦馨

![ok7a4257](https://user-images.githubusercontent.com/6755791/35494734-9fd539fc-04f7-11e8-8d5f-c2d21862ed9f.JPG)

![ok7a4298](https://user-images.githubusercontent.com/6755791/35494739-a538fe24-04f7-11e8-944c-5b3baa9cb29c.JPG)

他的分享主题是《灵雀云如何利用 CNI 接口在 Kubernetes 上实现 Pod 的静态 IP 功能》

CNI 作为 CNCF 的项目提供了构建容器网络的接口和类库，可以方便 kubernetes 扩展使用不同的网络模型，这次会介绍一下 CNI 的工作方式以及如何进行开发。同时会结合灵雀云的实践来介绍现有网络模型在传统环境存在的一些缺陷以及灵雀云如何根据 CNI 的接口实现的 pod 静态 IP 方面的工作。

⬇️ *本位讲师 slides 暂未开放*

### 第五个话题的 Speaker 是《HDFS 2.X 源码剖析》作者、今日头条基础架构研发工程师徐鹏

![ok7a4388](https://user-images.githubusercontent.com/6755791/35494759-bfb7459e-04f7-11e8-9ee1-1f9861a71d10.JPG)

<img width="1098" alt="screen shot 2018-01-29 at 1 25 05 pm" src="https://user-images.githubusercontent.com/6755791/35494799-01babc96-04f8-11e8-8738-d9bd21eab61b.png">

他的分享主题是《今日头条 Hadoop Yarn 调度实践》

Agenda
1.Hadoop 技术概述：简要介绍 Hadoop 平台的架构，发展历史以及演进
2.Hadoop 目前在头条的概况：介绍 Hadoop 平台是如何支持头条 1亿+ DAU的产品，我们在实践 Hadoop 时遇到了什么挑战，是如何解决的
3.未来的 Hadoop 在头条，未来 Hadoop 平台在头条的规划以及思考

<img width="1098" alt="screen shot 2018-01-29 at 1 25 37 pm" src="https://user-images.githubusercontent.com/6755791/35494800-03496896-04f8-11e8-9ad6-51bb0e376fc2.png">

<img width="1096" alt="screen shot 2018-01-29 at 1 26 06 pm" src="https://user-images.githubusercontent.com/6755791/35494801-04a37358-04f8-11e8-859d-63c92a69f207.png">

⬇️ *点击这里下载讲师 slides*<https://github.com/Lykosteng/schedule-container-meetup/blob/master/2018-01-20_beijing/s%26c_bj_xp_yarn.pdf>

-----以下为更多现场同学照片大放送-----

![ok7a3790](https://user-images.githubusercontent.com/6755791/35494817-353fdf7e-04f8-11e8-982e-fb0216982c3b.JPG)

![ok7a3792](https://user-images.githubusercontent.com/6755791/35494818-356a4c64-04f8-11e8-84b7-03a0bff8d50f.JPG)

![ok7a4054](https://user-images.githubusercontent.com/6755791/35494826-42f93b56-04f8-11e8-8ad1-90e1ab50e0fe.JPG)

![ok7a4222](https://user-images.githubusercontent.com/6755791/35494831-4c583d50-04f8-11e8-9524-36ae5167a1a6.JPG)

![ok7a4331](https://user-images.githubusercontent.com/6755791/35494833-4ee32210-04f8-11e8-8661-9aa059ee4255.JPG)

![ok7a4445](https://user-images.githubusercontent.com/6755791/35494834-5160b73c-04f8-11e8-8893-6d868cc7041e.JPG)

![ok7a3836](https://user-images.githubusercontent.com/6755791/35494842-5bfda038-04f8-11e8-98cb-7e562ee40e06.JPG)

![ok7a3915](https://user-images.githubusercontent.com/6755791/35494846-62676008-04f8-11e8-89e7-15bb28e89693.JPG)

![ok7a3909](https://user-images.githubusercontent.com/6755791/35494847-63b4eb38-04f8-11e8-9640-a0ab65776117.JPG)


感谢大家参加我们第一次的技术沙龙，希望以后能有更多的机会和大家在一起交流、沟通、共同学习，我们下次见哦

