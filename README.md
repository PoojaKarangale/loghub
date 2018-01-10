# loghub
Loghub maintains a collection of system logs, which are freely accessible for research purposes. Some of the logs are production data released from previous studies, some others are collected from real systems in our lab environment. Wherever possible, the logs are NOT sanitized, anonymized or modified in any way. All these logs amount to XX GB in size. We host only a small sample (2k lines) on Github for each dataset, please request the [raw datasets at Zenodo](https://zenodo.org/record/1144101#.WlYIzVWWbIU).

Logs currently available:


| Software System | Dataset Name | Time Span | #Messages | Raw Size | Compressed Size (.tar.gz) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Big data systems** |
| [HDFS](./HDFS) | HDFS-1 | 38.7 hours | 11,175,629 | 1.54GB | 152.01MB |
|  | HDFS-2 | xx | xx | xx | xx |
| [Hadoop](./Hadoop) | hadoop | N.A. | 394,308 | 49.78MB | 2.50MB |
| [Spark](./Spark) | Spark | xx | xx | xx | xx |
| [Zookeeper](./Zookeeper) | Zookeeper | 26.7 days | 74,380 | 10.18MB | 452KB |
| **Operating systems** |
| [Windows](./Windows) | Windows | 226.7 days | 114,608,388 | 27.36GB | 1.63GB |
| [Linux](./Linux) | Linux | 263.9 days | 25,567 | 2.30MB | 228KB |
| [Mac](./Mac) | Mac | xx | xx | xx | xx |
| Web applications |
| [Apache](./Apache) | Apache | xx | xx | xx | xx |
| **Mobile systems** |
| [Andriod](./Andriod) | Andriod | xx | xx | xx | xx |
| [HealthApp](./HealthApp) | HealthApp | xx | xx | xx | xx |
| **Supercomputers** |
| [BGL](./BGL) | BGL | 214.7 days | 4,747,963 | 725.77MB | 61.46MB |
| [HPC](./HPC) | HPC | xx | xx | xx | xx |
| [Thunderbird](./Thunderbird) | Thunderbird | xx | xx | xx | xx |
| **On-premises software** |
| [Proxifier](./Proxifier) | Proxifier | xx | xx | xx | xx |
| [OpenSSH](./OpenSSH) | SSH | xx | xx | xx | xx |


### Publications using these datasets
+ [**TDSC'17**] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [Towards Automated Log Parsing for Large-Scale Log Data Analysis](http://jiemingzhu.github.io/pub/pjhe_tdsc2017.pdf). IEEE Transactions on Dependable and Secure Computing (TDSC), 2017.
+ [**ICWS'17**] Pinjia He, Jieming Zhu, Zibin Zheng, Michael R. Lyu. [Drain: An Online Log Parsing Approach with Fixed Depth Tree](http://jiemingzhu.github.io/pub/pjhe_icws2017.pdf). IEEE International Conference on Web Services (ICWS), 2017.
+ [**ICSE'16**] Qingwei Lin, Hongyu Zhang, Jian-Guang Lou, Yu Zhang, Xuewei Chen. [Log Clustering Based Problem Identification for Online Service Systems](http://ieeexplore.ieee.org/document/7883294/). International Conference on Software Engineering (ICSE), 2016.
+ [**DSN'16**] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [An Evaluation Study on Log Parsing and Its Use in Log Mining](http://jiemingzhu.github.io/pub/pjhe_dsn2016.pdf). IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2016.
+ [**ISSRE'16**] Shilin He, Jieming Zhu, Pinjia He, Michael R. Lyu. [Experience Report: System Log Analysis for Anomaly Detection](http://jiemingzhu.github.io/pub/slhe_issre2016.pdf). IEEE International Symposium on Software Reliability Engineering (ISSRE), 2016.
+ [**KDD'09**] Adetokunbo Makanju, A. Nur Zincir-Heywood, Evangelos E. Milios. [Clustering Event Logs Using Iterative Partitioning](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.503.7668&rep=rep1&type=pdf). ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), 2009.
+ [**SOSP'09**] Wei Xu, Ling Huang, Armando Fox, David A. Patterson, Michael I. Jordan. [Detecting Large-Scale System Problems by Mining Console Logs](https://www.sigops.org/sosp/sosp09/papers/xu-sosp09.pdf). ACM Symposium on Operating Systems Principles (SOSP), 2009. 
+ [**DSN'07**] Adam J. Oliner, Jon Stearley. [What Supercomputers Say: A Study of Five System Logs](http://ieeexplore.ieee.org/document/4273008/). IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2007.



### License
The log datasets are freely available ONLY for research purposes. 


