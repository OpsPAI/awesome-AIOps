# awesome-AIOps
A curated list of awesome academic researches and industrial materials about Artificial Intelligence for IT Operations (AIOps).

- [Researchers](#researchers)
- [Industrial Materials](#industrial-materials)
  - [Competitions](#competitions)
  - [White Papers](#white-papers)
  - [Blogs & Tutorials & Magazines](#blogs--tutorials--magazines)
  - [Tools](#tools)
- [Papers](#papers)
  - [Talks](#talks)
  - [Survey & Empirical Study](#survey--empirical-study)
  - [Anomaly/Failure Detection](#anomalyfailure-detection)
  - [Failure Prediction](#failure-prediction)
  - [Failure Diagnosis](#failure-diagnosis)
  - [Incident/Alarm Management](#incidentalarm-management)
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

### Tools
- [**Log Analytics**] [LogPAI](https://github.com/logpai)
- [**Outlier Detection**] [PyOD](https://github.com/yzhao062/pyod)
- [**Fault Injection**] [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh)
- [**Fault Injection**] [ChaosBlade](https://github.com/chaosblade-io/chaosblade)

### Companies
- [Datadog](https://www.datadoghq.com/): A monitoring and security platform for cloud applications
- [必示 bizseer](https://www.bizseer.com/)
- [听云 TINGYUN](https://www.tingyun.com/lp.html): 端到端的全平台应用性能管理系统


## Papers

### Talks
- [Michael R. Lyu] [Reliability-Driven AIOps for Cloud Resilience (Keynote talk at ICSE'21)](http://ariselab.cse.cuhk.edu.hk/assets/files/ICSE2021_keynote_lyu.pdf)

### Survey & Empirical Study
- [CSUR'21] [A Survey on Automated Log Analysis for Reliability Engineering](https://arxiv.org/abs/2009.07237)
- [ESEC/FSE'20] [Towards intelligent incident management: why we need it and how we make it](https://dl.acm.org/doi/abs/10.1145/3368089.3417055)
- [arXiv'20] [A Systematic Mapping Study in AIOps](https://arxiv.org/abs/2012.09108)
- [ICSE'19] [AIOps: Real-World Challenges and Research Innovations](https://ieeexplore.ieee.org/document/8802836)
- [ISSRE'16] [Experience Report: System Log Analysis for Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/7774521)
- [ASE'13] [Software analytics for incident management of online services: An experience report](https://ieeexplore.ieee.org/document/6693105)

### Anomaly/Failure Detection
- [KDD'19] [Time-Series Anomaly Detection Service at Microsoft](https://dl.acm.org/doi/10.1145/3292500.3330680)
- [ESEC/FSE'18] [Identifying Impactful Service System Problems via Log Analysis](https://dl.acm.org/doi/10.1145/3236024.3236083)
- [CCS'17] [DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://dl.acm.org/doi/10.1145/3133956.3134015)

### Failure Prediction
- [OSDI'20] [Predictive and Adaptive Failure Mitigation to Avert Production Cloud VM Interruptions](https://www.usenix.org/conference/osdi20/presentation/levy)

### Failure Diagnosis
- [NSDI'20] [Gandalf: An Intelligent, End-To-End Analytics Service for Safe Deployment in Large-Scale Cloud Infrastructure](https://www.usenix.org/conference/nsdi20/presentation/li)

### Fault Analysis
- [FSE20] [Graph-based trace analysis for microservice architecture understanding and problem diagnosis](https://dl.acm.org/doi/10.1145/3368089.3417066)
- [TSE18] [Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study](https://ieeexplore.ieee.org/document/8580420/)

### Incident/Alarm Management
- [ESEC/FSE'20] [Identifying linked incidents in large-scale online service systems](https://dl.acm.org/doi/10.1145/3368089.3409768)
- [ESEC/FSE'20] [Efficient incident identification from multi-dimensional issue reports via meta-heuristic search](https://dl.acm.org/doi/abs/10.1145/3368089.3409741)
- [ICSE'20] [Understanding and Handling Alert Storm for Online Service Systems](https://dl.acm.org/doi/10.1145/3377813.3381363)
- [ESEC/FSE'20] [Efficient incident identification from multi-dimensional issue reports via meta-heuristic search](https://dl.acm.org/doi/abs/10.1145/3368089.3409741)
- [ESEC/FSE'20] [Real-time incident prediction for online service systems](https://dl.acm.org/doi/abs/10.1145/3368089.3409672)
- [ICSE'19] [An empirical investigation of incident triage for online service systems](https://dl.acm.org/doi/10.1109/ICSE-SEIP.2019.00020)
- [WWW'19] [Outage Prediction and Diagnosis for Cloud Service Systems](https://dl.acm.org/doi/10.1145/3308558.3313501)

## Datasets
- [CUHK] [Loghub](https://github.com/logpai/loghub)
- [Microsoft Azure] [Azure Public Dataset](https://github.com/Azure/AzurePublicDataset)
- [Tsinghua] [AIOps Challenge Dataset](http://iops.ai/dataset_list/)
- [Backblaze] [Hard Drive Dataset](https://www.backblaze.com/b2/hard-drive-test-data.html)
- [Baidu] [SMART Dataset of PAKDD CUP 2020](https://pan.baidu.com/share/link?shareid=189977&uk=4278294944#list/path=%2FS.M.A.R.T.dataset)


## Others

### Courses
- [Coursera] [Cloud-Based Network Design & Management Techniques](https://www.coursera.org/learn/cloud-based-network-design-and-management)
- [Tsinghua] [AIOps Course of Tsinghua](https://netman.aiops.org/courses/advanced-network-management-spring2021-course/)
