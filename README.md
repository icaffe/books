Table of contents
=================

<!--ts-->
  * [广告业务](#广告业务)
  * [模型工程](#模型工程)
  * [实时工程](#实时工程)
  * [用户行为建模](#用户行为兴趣)
  * [多任务建模](#多任务建模)
  * [召回模型](#召回模型)
  * [业界实践](#业界实践)
  * [框架相关](#框架相关)
  * [Flink 流式系统](#Flink 流式系统)
  * [Embedding](#Embedding)
  * [C++](#CPP)
  * [Java](#Java)
  * [NLP](#NLP)
  * [基础知识](#基础知识)
<!--te-->

## 广告业务

- [x] [谷歌的广告业务是如何赚钱的？郄小虎Tiger - 知乎](https://www.zhihu.com/question/32221970/answer/119083085)
- [ ] [搜索引擎公司是如何利用博弈论进行广告位拍卖的？ - 知乎](https://www.zhihu.com/question/57409967)
- [ ] [互联网广告拍卖机制设计](https://xinsong.github.io/2013/08/16/ad_auction_theory/)
- [ ] [互联网广告拍卖的数学描述及最优拍卖机制设计 - 掘金](https://juejin.im/post/5e4e0cb7518825494f7df389)
- [ ] [从央视到谷歌：聊一聊竞价广告的机制设计 | 爱范儿](https://www.ifanr.com/1061230)
- [ ] [为什么 Google 的搜索广告拍卖采用 GSP 机制，而不是 VCG 机制？ - 知乎](https://www.zhihu.com/question/30471881)
- [ ] [广告拍卖机制与点击率预估概述_人工智能_frankie110的专栏-CSDN博客](https://blog.csdn.net/frankie110/article/details/50209881)
- [ ] [谈谈广告平台的竞价原理：GFP,GSP,VCG - 知乎](https://zhuanlan.zhihu.com/p/20694813)
- [ ] [GSP — The Cinderella of Mechanism Design](https://arxiv.org/pdf/1701.05946.pdf)

## 模型工程
- [x] [使用tensorflow c++ api构建线上预测服务 - 篇3 - J.P.Liu's Blog](https://mathmach.com/832a0a1e/)
- [x] [基于TensorFlow Serving的深度学习在线预估 - 美团技术团队](https://tech.meituan.com/2018/10/11/tfserving-improve.html)
- [ ] [从阿里的User Interest Center看模型线上实时serving方法 - 知乎](https://zhuanlan.zhihu.com/p/111929212)
- [ ] [如何解决推荐系统工程难题——深度学习推荐模型线上serving？ - 知乎](https://zhuanlan.zhihu.com/p/77664408)
- [ ] [揭开YouTube深度推荐系统模型Serving之谜 - 知乎](https://zhuanlan.zhihu.com/p/61827629)


## 实时工程
- [x] [在线学习在爱奇艺信息流推荐业务中的探索与实践 - InfoQ](https://www.infoq.cn/article/lTHcDaZelZgC639P1P5q)
- [x] [浅谈流式模型训练体系 - 知乎](https://zhuanlan.zhihu.com/p/89512081)
- [x] [汽车之家推荐系统排序算法迭代之路 - InfoQ](https://www.infoq.cn/article/87gOLIaqWZW4moL0G9Ke)
- [x] [Flink 如何支持特征工程、在线学习、在线预测等 AI 场景？-阿里云开发者社区](https://developer.aliyun.com/article/749461)
- [x] [信息流推荐在凤凰新闻的业务实践 - InfoQ](https://www.infoq.cn/article/fNRRQhtuhaB2lh6jFM9h)
- [x] [实时数据流上的机器学习——Tensorflow on Flink - 知乎](https://zhuanlan.zhihu.com/p/55638891)
- [x] [蚂蚁金服核心技术：百亿特征实时推荐算法揭秘 - 知乎](https://zhuanlan.zhihu.com/p/53530167)
- [x] [双12根本不在话下，阿里首次揭秘扛过双11的千亿级特征分布式机器学习平台XPS-阿里云](https://yq.aliyun.com/articles/281155)
- [x] [一站式机器学习平台建设实践 - 美团技术团队](https://tech.meituan.com/2020/01/23/meituan-delivery-machine-learning.html)
- [x] [在线学习（Online Learning）导读 - 知乎](https://zhuanlan.zhihu.com/p/36410780)
- [ ] [实时个性化推荐介绍](https://mp.weixin.qq.com/s/UxVTdyH20xO0x0Lm0eTF1A)
- [ ] [天下武功，唯快不破，论推荐系统的「 实时性」 - 知乎](https://zhuanlan.zhihu.com/p/74813776)
- [ ] [如何增强推荐系统模型更新的「实时性」？ - 知乎](https://zhuanlan.zhihu.com/p/75597761)
- [ ] [Apache Flink在滴滴的应用与实践](https://mp.weixin.qq.com/s/xftJ8S3qbXgK1JSeOllcfg)


## 用户行为兴趣
- [x] [CTR预估问题没有“银弹”，比模型结构更重要的是什么？ - InfoQ](https://www.infoq.cn/article/Mfv1ZThAsPvrUSN*C69V)
- [x] [详解阿里之Deep Interest Evolution Network(AAAI 2019) - 知乎](https://zhuanlan.zhihu.com/p/50758485)
- [ ] [阿里Deep Session Interest Network解读 - 知乎](https://zhuanlan.zhihu.com/p/71695849)
- [ ] [阿里推荐算法（MIND）：基于动态路由的用户多兴趣网络 - 知乎](https://zhuanlan.zhihu.com/p/76495890)
- [ ] [如何刻画用户的多样兴趣——MIND network阅读笔记 - 知乎](https://zhuanlan.zhihu.com/p/68897114)


## 多任务建模
- [x] [阿里CVR预估模型之ESMM - 知乎](https://zhuanlan.zhihu.com/p/57481330)
- [x] [Youtube 排序系统：Recommending What Video to Watch Next - 知乎](https://zhuanlan.zhihu.com/p/82584437)
- [x] [Multi-task多任务学习在推荐算法中的应用 - 知乎](https://zhuanlan.zhihu.com/p/109835504)
- [x] [从谷歌到阿里，谈谈工业界推荐系统多目标预估的两种范式 - 知乎](https://zhuanlan.zhihu.com/p/125507748)
- [ ] [详解谷歌之多任务学习模型MMoE(KDD 2018) - 知乎](https://zhuanlan.zhihu.com/p/55752344)
- [ ] [多任务学习模型详解：Multi-gate Mixture-of-Experts（MMoE ，Google，KDD2018）](https://mp.weixin.qq.com/s?__biz=MzUzMTgyNjUwOA==&mid=2247483916&idx=1&sn=c17bb53ed442751a91ef413de651bb71&chksm=fabdd02fcdca593996f173a68f34206e3a2432677f3eaa65ae05f56811ac40f152685d6ef2af&token=219959589&lang=zh_CN#rd)
- [ ] [稀疏共享：当多任务学习遇见彩票假设 - 知乎](https://zhuanlan.zhihu.com/p/93830096)


## 召回模型
- [ ] [推荐召回算法之深度召回模型串讲 - 知乎](https://zhuanlan.zhihu.com/p/63343894)
- [ ] [深入理解推荐系统：召回 - 知乎](https://zhuanlan.zhihu.com/p/115690499)
- [ ] [推荐系统召回四模型之：全能的FM模型 - 知乎](https://zhuanlan.zhihu.com/p/58160982)
- [ ] [TDM介绍 – d0evi1的博客](http://d0evi1.com/tdm/)
- [ ] [DSSM：深度语义匹配模型（及其变体CLSM、LSTM-DSSM） - 郭耀华 - 博客园](https://www.cnblogs.com/guoyaohua/p/9229190.html)
- [ ] [推荐系统与CTR预估， 基于深度学习（一):召回思路及模型串讲 - Nick's Tech Blog](http://fanding.xyz/2018/05/01/%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F%E4%B8%8ECTR%E9%A2%84%E4%BC%B0,%E5%9F%BA%E4%BA%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0-%E4%B8%80-%E5%8F%AC%E5%9B%9E%E6%80%9D%E8%B7%AF%E5%8F%8A%E6%A8%A1%E5%9E%8B%E4%B8%B2%E8%AE%B2/)


## 业界实践
- [x] [镶嵌在互联网技术上的明珠：漫谈深度学习时代点击率预估技术进展 - 知乎](https://zhuanlan.zhihu.com/p/54822778)
- [ ] [揭秘微信"看一看"是如何为你推荐的](https://mp.weixin.qq.com/s/nFThC8hcA1wWNb_nskiSRg)
- [ ] [热点挖掘技术在微信看一看中的应用](https://mp.weixin.qq.com/s/oMNy-g2DxUnsGErefQBkyg)
- [x] [深度学习在省钱快报推荐排序中的应用与实践 - InfoQ](https://www.infoq.cn/article/S442HaOtfMk72vgikZZP)
- [ ] [美图个性化推送的 AI 探索之路 - InfoQ](https://www.infoq.cn/article/Y1uHWtLHTsLJheBIHVS8)
- [ ] [深度学习在花椒直播中的应用——推荐系统冷启动算法 - 掘金](https://juejin.im/post/5e7974a2e51d45271515850f)
- [ ] [算法调研-微信看一看Embedding - 知乎](https://zhuanlan.zhihu.com/p/102918124)
- [ ] [广告CTR预估中用户行为学习和记忆建模](https://mp.weixin.qq.com/s/xDjO1yhOm57ZfuRofCf0Uw)
- [ ] [增加User Memory Embedding的深度点击率预估模型 – Semocean](http://www.semocean.com/%e5%a2%9e%e5%8a%a0user-memory-embedding%e7%9a%84%e6%b7%b1%e5%ba%a6%e7%82%b9%e5%87%bb%e7%8e%87%e9%a2%84%e4%bc%b0%e6%a8%a1%e5%9e%8b/)
- [ ] [WWW 2020关于深度推荐系统与CTR预估相关的论文](https://mp.weixin.qq.com/s/KITQYRFH6SD_2Y-f-2pyJA)
- [ ] [CTR预估在动态样式建模和特征表达学习方面的进展](https://mp.weixin.qq.com/s/YZtKh5-xxhDwLcOJVDvqtw)
- [ ] [推荐系统遇上深度学习(八十二)-[阿里]可视化分析点击率预估模型 - 简书](https://www.jianshu.com/p/7c3344d79405)
- [ ] [推荐系统遇上深度学习(八十一)-[阿里]DMR：Matching和Ranking相结合的点击率预估模型 - 简书](https://www.jianshu.com/p/60eed27e06d4)
- [ ] [最新边信息推荐系统综述 | Survey on Recommendations with Side Information](https://mp.weixin.qq.com/s/3DzZ5kG4vQ5OJhQ8Fly25A)
- [x] [深入浅出排序学习：写给程序员的算法系统开发实践 - 美团技术团队](https://tech.meituan.com/2018/12/20/head-in-l2r.html)
- [ ] [WWW2020推荐系统论文合集(已分类整理)](https://mp.weixin.qq.com/s/pJM6HxTtp8p3J2O1c-lf3Q)
- [ ] [谷歌最新双塔DNN召回模型——应用于YouTube大规模视频推荐场景 - 知乎](https://zhuanlan.zhihu.com/p/128988454)
- [ ] [DLP-KDD全部文章及资源，覆盖GNN、Graph Emb、Transformer等业界前沿领域 - 知乎](https://zhuanlan.zhihu.com/p/135919198)


## 框架相关
- [ ] [机器学习平台 Goblin 的实践 - 知乎](https://zhuanlan.zhihu.com/p/129327848)
- [ ] [机器学习平台在Kubernetes上的实践 - 知乎](https://zhuanlan.zhihu.com/p/137678661)
- [ ] [机器学习框架上的一些实践 - 知乎](https://zhuanlan.zhihu.com/p/76541337)
- [ ] [TensorFlow做Sparse Machine Learning - 知乎](https://zhuanlan.zhihu.com/p/50793463)
- [ ] [极简入门TensorFlow C++源码 - 知乎](https://zhuanlan.zhihu.com/p/78503581)
- [ ] [极简入门TensorFlow 内存管理 - 知乎](https://zhuanlan.zhihu.com/p/94467054)
- [ ] [大白话讲nnvm - 知乎](https://zhuanlan.zhihu.com/p/65464435)
- [ ] [ps-lite代码解析 - 知乎](https://zhuanlan.zhihu.com/p/60584612)
- [ ] [分布式训练的方案和效率对比 - 知乎](https://zhuanlan.zhihu.com/p/50116885)


## Flink 流式系统
- [ ] [zhisheng17/flink-learning 含 Flink 入门、概念、原理、实战、性能调优、源码解析等内容](https://github.com/zhisheng17/flink-learning)
- [ ] [评:Streaming System(简直炸裂,强势安利) - 知乎](https://zhuanlan.zhihu.com/p/43301661)
- [ ] [端到端一致性,流系统Spark/Flink/Kafka/DataFlow对比总结(压箱宝具呕血之作) - 知乎](https://zhuanlan.zhihu.com/p/77677075)
- [ ] [pythonbooks/Streaming Systems](https://github.com/iamseancheney/pythonbooks/blob/master/Streaming%20Systems%20-%20Tyler%20Akidau.pdf)

## Embedding
- [ ] [图表示学习Graph Embedding综述](https://mp.weixin.qq.com/s/q1QsSplzZ_TMf0wvZ19hBg)
- [ ] [Embedding技术在58同城推荐中的应用](https://mp.weixin.qq.com/s/8bP62cSUVFL38AesLSxqvQ)
- [ ] [全面理解PinSage - 知乎](https://zhuanlan.zhihu.com/p/133739758)


## CPP
- [ ] [C++ 编译初步 | 吴良超的学习笔记](http://wulc.me/2018/11/24/C++%20%E7%BC%96%E8%AF%91%E5%88%9D%E6%AD%A5/)
- [ ] [cmake学习记录 - 知乎](https://zhuanlan.zhihu.com/p/38736401)
- [ ] [makefile 文件的编写 - kzangv - 博客园](https://www.cnblogs.com/kzang/articles/2679933.html)
- [ ] [C++ 基础之引用计数 - 知乎](https://zhuanlan.zhihu.com/p/104326499)
- [ ] [blade-build/user_manual.md at master · chen3feng/blade-build](https://github.com/chen3feng/blade-build/blob/master/doc/zh_CN/user_manual.md)

## Java
- [ ] [Java教程 - 廖雪峰的官方网站](https://www.liaoxuefeng.com/wiki/1252599548343744)
- [ ] [doocs/advanced-java: 进阶知识完全扫盲：涵盖高并发、分布式、高可用、微服务、海量数据处理等](https://github.com/doocs/advanced-java)


## NLP
- [ ] [Rethink深度学习中的Attention机制 - 知乎](https://zhuanlan.zhihu.com/p/125145283)
- [ ] [Transformer 在美团搜索排序中的实践 - 美团技术团队](https://tech.meituan.com/2020/04/16/transformer-in-meituan.html)
- [ ] [Attention机制在深度学习推荐算法中的应用](https://mp.weixin.qq.com/s/1LYyiDJBDKVgNjc7a1Qc4A)


## 基础知识
- [x] [频率学派和贝叶斯学派 - 知乎](https://zhuanlan.zhihu.com/p/54125819)
- [x] [贝叶斯学派与频率学派有何不同？ - 知乎](https://www.zhihu.com/question/20587681)
- [x] [如何通俗理解 beta 分布？ - 知乎](https://www.zhihu.com/question/30269898)
- [x] [CTR预估中的贝叶斯平滑方法（一）原理及实验介绍 - 笨兔勿应 - 博客园](https://www.cnblogs.com/bentuwuying/p/6389222.html)
- [x] [CTR预估中的贝叶斯平滑方法（二）参数估计和代码实现 - 笨兔勿应 - 博客园](https://www.cnblogs.com/bentuwuying/p/6498370.html)
- [x] [转化率（CTR）预测的贝叶斯平滑 - 小平子的专栏 - CSDN博客](https://blog.csdn.net/jinping_shi/article/details/78334362)
- [x] [ctr平滑 – d0evi1的博客](http://d0evi1.com/ctr-smooth/)

