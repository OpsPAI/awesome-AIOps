# awesome-AIOps
A curated list of awesome academic researches and industrial materials about Artificial Intelligence for IT Operations (AIOps).

- [Researchers](#researchers)
- [Industrial Materials](#industrial-materials)
  - [Competitions](#competitions)
  - [White Papers](#white-papers)
  - [Blogs & Tutorials & Magazines](#blogs--tutorials--magazines)
  - [Benchmarks](#benchmarks)
  - [Tools](#tools)
  - [Companies](#companies)
- [Academic Materials](#academic-materials)
  - [Talks](#talks)
  - [Workshops](#workshops)
- [Papers](#papers)
  - [Survey & Empirical Study](#survey--empirical-study)
  - [Dependency and Tracing](#dependency-and-tracing)
  - [Anomaly and Failure Detection](#anomaly-and-failure-detection)
  - [Failure Prediction](#failure-prediction)
  - [Failure Diagnosis](#failure-diagnosis)
  - [Fault Analysis](#fault-analysis)
  - [Incident and Alarm Management](#incident-and-alarm-management)
- [Datasets](#datasets)
- [Others](#others)
  - [Courses](#courses)

## Researchers
| China (& HK SAR) | |||
| :---------| :------ | :------ | :------ |
| [Michael R. Lyu](http://www.cse.cuhk.edu.hk/lyu/), CUHK | [Dongmei Zhang](https://www.microsoft.com/en-us/research/people/dongmeiz/), Microsoft | [Pengfei Chen](http://sdcs.sysu.edu.cn/content/3747), SYSU | [Dan Pei](https://netman.aiops.org/~peidan/), Tsinghua |
| [Xin Peng](https://cspengxin.github.io/), Fudan ||||
| **USA** ||||
| [Ryan Huang](https://www.cs.jhu.edu/~huang/), JHU | [Yingnong Dang](https://scholar.google.com.hk/citations?user=InqtwxcAAAAJ&hl=en), Microsoft |||
| **Europe** |||||
| [Odej Kao](https://www.cit.tu-berlin.de/kao/), TU Berlin ||||
| **Australia** ||||
| [Hongyu Zhang](http://hongyujohn.github.io/), UON ||||


## Industrial Materials
### Competitions
- [AIOps Challenge] [A series of AIOps competitions hosted by Tsinghua University](http://iops.ai/)
- [PAKDD2020] [Alibaba AIOps Competition](https://tianchi.aliyun.com/competition/entrance/231775/introduction?lang=en-us)

### White Papers
- [VMware] [Proactive Incident and Problem Management](https://docplayer.net/8854482-Proactive-incident-and-problem-management.html)
- [GREATOPS 高效运维社区] [《企业级 AIOps 实施建议》白皮书](https://pic.huodongjia.com/ganhuodocs/2018-04-16/1523873064.74.pdf)
- [Awesome Open Source] [Aiops Handbook](https://awesomeopensource.com/project/chenryn/aiops-handbook)

### Blogs & Tutorials & Magazines
- [Moogsoft] [What is AIOps?](https://www.moogsoft.com/resources/aiops/guide/everything-aiops/)
- [Microsoft] [Advancing Azure service quality with artificial intelligence: AIOps](https://azure.microsoft.com/en-us/blog/advancing-azure-service-quality-with-artificial-intelligence-aiops/)

### Benchmarks
- [Fudan] [Train Ticket (A Benchmark Microservice System)](https://github.com/FudanSELab/train-ticket)
- [Weaveworks] [Sock Shop (A Microservices Demo Application)](https://microservices-demo.github.io/)

### Tools
- [Log Analytics] [LogPAI](https://github.com/logpai)
- [Outlier Detection] [PyOD](https://github.com/yzhao062/pyod)
- [Anomaly Detection] [ADTK](https://github.com/arundo/adtk)
- [Anomaly Detection] [PySAD](https://github.com/selimfirat/pysad)
- [Fault Injection] [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh)
- [Fault Injection] [ChaosBlade](https://github.com/chaosblade-io/chaosblade)
- [Performance Monitoring] [Netdata](https://www.netdata.cloud/)
- [Anomaly Detection Labeling Tool] [Microsoft TagAnomaly](https://github.com/Microsoft/TagAnomaly)
- [Serverless App Dev. Framework] [AWS Serverless Application Model (AWS SAM)](https://github.com/aws/serverless-application-model)

### Companies
- [Datadog](https://www.datadoghq.com/): A monitoring and security platform for cloud applications
- [必示 bizseer](https://www.bizseer.com/)
- [听云 TINGYUN](https://www.tingyun.com/lp.html): 端到端的全平台应用性能管理系统


## Academic Materials

### Talks
- [Michael R. Lyu] [Reliability-Driven AIOps for Cloud Resilience (Keynote talk at ICSE'21)](http://ariselab.cse.cuhk.edu.hk/assets/files/ICSE2021_keynote_lyu.pdf)

### Workshops
- [ICSE21 Workshop on Cloud Intelligence](http://cloudintelligenceworkshop.org/index.html)
- [AAAI-20 Workshop on Cloud Intelligence](http://cloudintelligenceworkshop.org/2020/index.html)
- [AIOPS 2020 (International Workshop on Artificial Intelligence for IT Operations)](https://aiopsworkshop.github.io/)


## Papers

### Survey & Empirical Study
- [arXiv'21] [Experience Report: Deep Learning-based System Log Analysis for Anomaly Detection](https://arxiv.org/abs/2107.05908)
- [CSUR'21] [A Survey on Automated Log Analysis for Reliability Engineering](https://arxiv.org/abs/2009.07237)
- [ESEC/FSE'20] [Towards intelligent incident management: why we need it and how we make it](https://dl.acm.org/doi/abs/10.1145/3368089.3417055)
- [arXiv'20] [A Systematic Mapping Study in AIOps](https://arxiv.org/abs/2012.09108)
- [ICSE'19] [AIOps: Real-World Challenges and Research Innovations](https://ieeexplore.ieee.org/document/8802836)
- [ISSRE'16] [Experience Report: System Log Analysis for Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/7774521)
- [ASE'13] [Software analytics for incident management of online services: An experience report](https://ieeexplore.ieee.org/document/6693105)

### Dependency and Tracing
- [NSDI'07] [X-Trace: A Pervasive Network Tracing Framework](https://www.usenix.org/conference/nsdi-07/x-trace-pervasive-network-tracing-framework)
- [HotNets'06] [Discovering Dependencies for Network Management](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/11/hotnets06.pdf)

### Anomaly and Failure Detection
- [KDD'19] [Time-Series Anomaly Detection Service at Microsoft](https://dl.acm.org/doi/10.1145/3292500.3330680)
- [ESEC/FSE'18] [Identifying Impactful Service System Problems via Log Analysis](https://dl.acm.org/doi/10.1145/3236024.3236083)
- [CCS'17] [DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://dl.acm.org/doi/10.1145/3133956.3134015)

### Failure Prediction
- [OSDI'20] [Predictive and Adaptive Failure Mitigation to Avert Production Cloud VM Interruptions](https://www.usenix.org/conference/osdi20/presentation/levy)
- [ESEC/FSE'18] [Predicting Node Failure in Cloud Service Systems](https://dl.acm.org/doi/10.1145/3236024.3236060)

### Failure Diagnosis
- [OSDI'20] [FIRM: An Intelligent Fine-grained Resource Management Framework for SLO-Oriented Microservices](https://www.usenix.org/conference/osdi20/presentation/qiu)
- [NSDI'20] [Gandalf: An Intelligent, End-To-End Analytics Service for Safe Deployment in Large-Scale Cloud Infrastructure](https://www.usenix.org/conference/nsdi20/presentation/li)

### Fault Analysis
- [FSE20] [Graph-based trace analysis for microservice architecture understanding and problem diagnosis](https://dl.acm.org/doi/10.1145/3368089.3417066)
- [TSE18] [Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study](https://ieeexplore.ieee.org/document/8580420/)

### Incident and Alarm Management
- [ASE'20] [How Incidental are the Incidents?: Characterizing and Prioritizing Incidents for Large-Scale Online Service Systems](https://dl.acm.org/doi/10.1145/3324884.3416624)
- [ESEC/FSE'20] [Identifying linked incidents in large-scale online service systems](https://dl.acm.org/doi/10.1145/3368089.3409768)
- [ESEC/FSE'20] [Efficient incident identification from multi-dimensional issue reports via meta-heuristic search](https://dl.acm.org/doi/abs/10.1145/3368089.3409741)
- [ESEC/FSE'20] [Real-time incident prediction for online service systems](https://dl.acm.org/doi/abs/10.1145/3368089.3409672)
- [ESEC/FSE'20] [How to mitigate the incident? an effective troubleshooting guide recommendation technique for online service systems](https://dl.acm.org/doi/abs/10.1145/3368089.3417054)
- [ICSE'20] [Understanding and Handling Alert Storm for Online Service Systems](https://dl.acm.org/doi/10.1145/3377813.3381363)
- [HotOS'19] [What bugs cause production cloud incidents?](https://dl.acm.org/doi/10.1145/3317550.3321438)
- [ASE'19] [Continuous Incident Triage for Large-Scale Online Service Systems](https://dl.acm.org/doi/10.1109/ASE.2019.00042)
- [ICSE'19] [An empirical investigation of incident triage for online service systems](https://dl.acm.org/doi/10.1109/ICSE-SEIP.2019.00020)
- [WWW'19] [Outage Prediction and Diagnosis for Cloud Service Systems](https://dl.acm.org/doi/10.1145/3308558.3313501)
- [KDD'14] [Correlating Events with Time Series for Incident Diagnosis](https://dl.acm.org/doi/10.1145/2623330.2623374)

## Datasets
- [CUHK] [Loghub](https://github.com/logpai/loghub)
- [Microsoft Azure] [Azure Public Dataset](https://github.com/Azure/AzurePublicDataset)
- [Tsinghua] [AIOps Challenge Dataset](http://iops.ai/dataset_list/)
- [Google] [Cluster Traces](https://github.com/google/cluster-data)
- [Backblaze] [Hard Drive Dataset](https://www.backblaze.com/b2/hard-drive-test-data.html)
- [Baidu] [SMART Dataset of PAKDD CUP 2020](https://pan.baidu.com/share/link?shareid=189977&uk=4278294944#list/path=%2FS.M.A.R.T.dataset)


## Others

### Courses
- [Coursera] [Cloud-Based Network Design & Management Techniques](https://www.coursera.org/learn/cloud-based-network-design-and-management)
- [Tsinghua] [AIOps Course of Tsinghua](https://netman.aiops.org/courses/advanced-network-management-spring2021-course/)
