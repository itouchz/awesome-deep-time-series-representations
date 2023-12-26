# Deep Learning for Universal Representations of Time Series

This is a repository to help all readers who are interested in learning universal representations of time series with deep learning.

If your papers are missing or you have other requests, please contact patara.t@ku.th, post an issue, or create a pull request.
We will update this repository a regular basis in accordance with the top-tier conference publication cycles to maintain up-to-date.

> **Accompany Paper**: Deep Learning for Universal Representations of Time Series: A Survey _submitted to_ ACM Computing Surveys
```bibtex
TBD
```

## Proposed Taxonomy
![proposed taxonomy](/taxonomy.png "Taxonomy regarding Deep Learning for Universal Representations of Time Series")

## Contents
- [Related Survey Papers](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#related-surveys)
  - [Time-Series Data Mining and Analysis](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#time-series-data-mining-and-analysis)
  - [General Representation Learning](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#representation-learning)
- [Research Papers](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#research-papers)
  - [Architecture-based Approaches](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#neural-architecture-based-approaches)
  - [Learning-based Approaches](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#learning-based-approaches)
  - [Data-Centric Approaches](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#data-centric-approaches)
- [Other Repositories](https://github.com/itouchz/awesome-deep-time-series-representations/tree/main#neighbor-repositories)

## Related Surveys (Latest Update: October, 2023)

### Time-Series Data Mining and Analysis
| **Title**                                                                                         |                  **Affiliation**                  |              **Venue**              | **Year** |
|---------------------------------------------------------------------------------------------------|:-------------------------------------------------:|:-----------------------------------:|:--------:|
| [Discrete Wavelet Transform-based Time Series Analysis and Mining](https://dl.acm.org/doi/abs/10.1145/1883612.1883613)                                  |               University of Maryland              |               ACM CSUR              |   2011   |
| [Time-Series Data Mining](https://dl.acm.org/doi/10.1145/2379776.2379788)                                                                           |                       IRCAM                       |               ACM CSUR              |   2012   |
| [A Review of Unsupervised Feature Learning and Deep Learning for Time-Series Modeling](https://www.sciencedirect.com/science/article/pii/S0167865514000221)              |                 Örebro University                 |     Pattern Recognition Letters     |   2014   |
| [Time-series clustering – A decade review](https://www.sciencedirect.com/science/article/pii/S0306437915000733)                                                          |                University of Malaya               |         Information Systems         |   2015   |
| [Deep Learning for Time-Series Analysis](https://arxiv.org/abs/1701.01887)                                                            |            University of Kaiserslautern           |                arXiv                |   2017   |
| [A survey of methods for time series change point detection](https://link.springer.com/article/10.1007/s10115-016-0987-z)                                        |            Washington State University            |                 KAIS                |   2017   |
| [Survey on time series motif discovery](https://wires.onlinelibrary.wiley.com/doi/full/10.1002/widm.1199)                                                             | Ostwestfalen-Lippe University of Applied Sciences |                 WIDM                |   2017   |
| [Wavelet Transform Application for/in Non-Stationary Time-Series Analysis: A Review](https://www.mdpi.com/2076-3417/9/7/1345)                |   Ecole Nationale des Sciences de l’Informatique  |        MDPI Applied Sciences        |   2019   |
| [Deep learning for time series classification: a review](https://link.springer.com/article/10.1007/s10618-019-00619-1)                                            |              Université Haute Alsace              | Data Mining and Knowledge Discovery |   2019   |
| [Anomaly Detection for IoT Time-Series Data: A Survey](https://ieeexplore.ieee.org/abstract/document/8926446)                                              |                University of Keele                |              IEEE IoT-J             |   2019   |
| [A Review of Deep Learning Methods for Irregularly Sampled Medical Time Series Data](https://arxiv.org/abs/2010.12493)                |                 Peking University                 |                arXiv                |   2020   |
| [Approaches and Applications of Early Classification of Time Series: A Review](https://ieeexplore.ieee.org/abstract/document/9207873/)                      |   Indian Institute of Technology (BHU) Varanasi   |               IEEE TAI              |   2020   |
| [A Survey on Principles, Models and Methods for Learning from Irregularly Sampled Time Series](https://arxiv.org/abs/2012.00168)      |        University of Massachusetts Amherst        |      NeurIPS Workshop on ML-RSA     |   2020   |
| [A Review of Deep Learning Models for Time Series Prediction](https://ieeexplore.ieee.org/document/8742529)                                       |          Dalian University of Technology          |         IEEE Sensors Journal        |   2021   |
| [An empirical survey of data augmentation for time series classification with neural networks](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0254841)      |                 Kyushu University                 |               PLOS ONE              |   2021   |
| [Time-series forecasting with deep learning: a survey](https://royalsocietypublishing.org/doi/full/10.1098/rsta.2020.0209)                                              |                University of Oxford               |          Phil.Trans.R.Soc.A         |   2021   |
| [A Review on Outlier/Anomaly Detection in Time Series Data](https://dl.acm.org/doi/abs/10.1145/3444690)                                         |      Basque Research and Technology Alliance      |               ACM CSUR              |   2021   |
| [A Review of Time-Series Anomaly Detection Techniques: A Step to Future Perspectives](https://link.springer.com/chapter/10.1007/978-3-030-73100-7_60)               |              University of Newcastle              |                 FICC                |   2021   |
| [Deep Learning for Anomaly Detection in Time-Series Data: Review, Analysis, and Guidelines](https://ieeexplore.ieee.org/abstract/document/9523565)         |             Seoul National University             |             IEEE Access             |   2021   |
| [Time Series Data Augmentation for Deep Learning: A Survey](https://www.ijcai.org/proceedings/2021/0631.pdf)                                         |                   Alibaba Group                   |                IJCAI                |   2021   |
| [An Experimental Review on Deep Learning Architectures for Time Series Forecasting](https://www.worldscientific.com/doi/abs/10.1142/S0129065721300011)                 |               University of Sevilla               |                 IJNS                |   2021   |
| [Experimental Comparison and Survey of Twelve Time Series Anomaly Detection Algorithms](https://jair.org/index.php/jair/article/view/12698)             |                       Verint                      |                 JAIR                |   2021   |
| [Causal inference for time series analysis: problems, methods and evaluation](https://link.springer.com/article/10.1007/s10115-021-01621-0)                       |              Arizona State University             |                 KAIS                |   2021   |
| [End-to-end deep representation learning for time series clustering: a comparative study](https://link.springer.com/article/10.1007/s10618-021-00796-y)           |             Université de Haute Alsace            | Data Mining and Knowledge Discovery |   2022   |
| [Survey and Evaluation of Causal Discovery Methods for Time Series](https://www.jair.org/index.php/jair/article/view/13428)                                 |             Université Grenoble Alpes             |                 JAIR                |   2022   |
| [A Review of Recurrent Neural Network-Based Methods in Computational Physiology](https://ieeexplore.ieee.org/abstract/document/9705533)                    |              University of Pittsburgh             |              IEEE TNNLS             |   2022   |
| [Deep Learning for Time Series Anomaly Detection: A Survey](https://arxiv.org/abs/2211.05244)                                                            |          Monash University        |              arXiv              |   2022   |
| [Deep Learning for Time Series Forecasting: Tutorial and Literature Survey](https://dl.acm.org/doi/full/10.1145/3533382)                                            |          Amazon Research          |             ACM CSUR            |   2022   |
| [Transformers in Time Series: A Survey](https://arxiv.org/abs/2202.07125)                                                             |                   Alibaba Group                   |                IJCAI                |   2023   |
| [Deep Learning for Time Series Classification and Extrinsic Regression: A Current Survey](https://arxiv.org/abs/2302.02515)           |                 Monash University                 |                arXiv                |   2023   |
| [Label-efficient Time Series Representation Learning: A Review](https://arxiv.org/abs/2302.06433)                                     |          Nanyang Technological University         |                arXiv                |   2023   |
| [Neural Time Series Analysis with Fourier Transform: A Survey](https://arxiv.org/abs/2302.02173)                                      |          Beijing Institute of Technology          |                arXiv                |   2023   |
| [A Survey on Dimensionality Reduction Techniques for Time-Series Data](https://ieeexplore.ieee.org/document/10107391)                              |           University of Colorado Boulder          |             IEEE Access             |   2023   |
| [Long sequence time-series forecasting with deep learning: A survey](https://www.sciencedirect.com/science/article/pii/S1566253523001355)                                |            Southwest Jiaotong University          |          Information Fusion         |   2023   |
| [Data Augmentation techniques in time series domain: a survey and taxonomy](https://link.springer.com/article/10.1007/s00521-023-08459-3)                         |         Universidad Politécnica de Madrid         |   Neural Computing & Applications   |   2023   |
| [Diffusion Models for Time Series Applications: A Survey](https://arxiv.org/abs/2305.00624)                                           |                University of Sydney               |                arXiv                |   2023   |
| [A Survey on Time-Series Pre-Trained Models](https://arxiv.org/abs/2305.10716)                                                        |        South China University of Technology       |                arXiv                |   2023   |
| [Self-Supervised Contrastive Learning for Medical Time Series: A Systematic Review](https://www.mdpi.com/1424-8220/23/9/4221)                 |                  RMIT University                  |             MDPI Sensors            |   2023   |
| [Self-Supervised Learning for Time Series Analysis: Taxonomy, Progress, and Prospects](https://arxiv.org/abs/2306.10125) | Zhejiang University | arXiv | 2023 |
| [Unsupervised Representation Learning for Time Series: A Review](https://arxiv.org/abs/2308.01578) |  Shandong University | arXiv | 2023 |
| [Large Models for Time Series and Spatio-Temporal Data: A Survey and Outlook](https://arxiv.org/abs/2310.10196) | Monash University | arXiv | 2023 |


### Representation Learning
| **Title**                                                                                                            |          **Affiliation**          |            **Venue**            | **Year** |
|----------------------------------------------------------------------------------------------------------------------|:---------------------------------:|:-------------------------------:|:--------:|
| [Representation Learning: A Review and New Perspectives](https://ieeexplore.ieee.org/document/6472238)                                                               |       University of Montreal      |            IEEE TPAMI           |   2013   |
| [A Survey of Multi-View Representation Learning](https://ieeexplore.ieee.org/abstract/document/8471216)                                                                       |        Zhejiang University        |            IEEE TKDE            |   2019   |
| [Deep Multimodal Representation Learning: A Survey](https://ieeexplore.ieee.org/abstract/document/8715409/)                                                                    |         Fuzhou University         |           IEEE Access           |   2019   |
| [A Survey on Representation Learning for User Modeling](https://www.ijcai.org/proceedings/2020/0695.pdf)                                                                |       University of Georgia       |              IJCAI              |   2020   |
| [A survey on deep geometry learning: From a representation perspective](https://link.springer.com/article/10.1007/s41095-020-0174-8)                                                |    Chinese Academy of Sciences    |    Computational Visual Media   |   2020   |
| [A Review on Deep Learning Approaches for 3D Data Representations in Retrieval and Classifications](https://ieeexplore.ieee.org/document/9043500/) |                 Xiamen University                 |             IEEE Access             |   2020   |
| [Contrastive Representation Learning: A Framework and Review](https://ieeexplore.ieee.org/abstract/document/9226466)                                                          |       Dublin City University      |           IEEE Access           |   2020   |
| [Beyond Just Vision: A Review on Self-Supervised Representation Learning on Multimodal and Temporal Data](https://arxiv.org/abs/2206.02353)              |          RMIT University          |              arXiv              |   2022   |
| [Self-Supervised Representation Learning: Introduction, advances, and challenges](https://ieeexplore.ieee.org/abstract/document/9770283)                                      |      University of Edinburgh      | IEEE Signal Processing Magazine |   2022   |
| [A Brief Overview of Universal Sentence Representation Methods: A Linguistic View](https://dl.acm.org/doi/10.1145/3482853)                                     |             KU Leuven             |             ACM CSUR            |   2022   |
| [Network Representation Learning: From Preprocessing, Feature Extraction to Node Embedding](https://dl.acm.org/doi/full/10.1145/3491206)                            |         Soochow University        |             ACM CSUR            |   2022   |
| [Evaluation Methods for Representation Learning: A Survey](https://www.ijcai.org/proceedings/2022/0776.pdf)                                                             |        University of Tokyo        |              IJCAI              |   2022   |
| [Self-Supervised Speech Representation Learning: A Review](https://ieeexplore.ieee.org/abstract/document/9893562)                                                             |                Meta               |            IEEE JSTSP           |   2022   |
| [A Survey on Hypergraph Representation Learning](https://dl.acm.org/doi/abs/10.1145/3605776)                                                                       |  Università degli Studi di Torino |             ACM CSUR            |   2023   |
| [Representation learning for knowledge fusion and reasoning in Cyber–Physical–Social Systems: Survey and perspectives](https://www.sciencedirect.com/science/article/pii/S156625352200135X) |         Hainan University         |        Information Fusion       |   2023   |
| [Survey of Deep Representation Learning for Speech Emotion Recognition](https://ieeexplore.ieee.org/abstract/document/9543566)                                                | University of Southern Queensland |            IEEE TAFFC           |   2023   |
| [Graph Representation Learning and Its Applications: A Survey](https://www.mdpi.com/1424-8220/23/8/4168)                                                         |    Catholic University of Korea   |           MDPI Sensors          |   2023   |
| [Graph Representation Learning Meets Computer Vision: A Survey](https://ieeexplore.ieee.org/abstract/document/9844822)                                                        |         Xidian University         |             IEEE TAI            |   2023   |
| [A Comprehensive Survey on Deep Graph Representation Learning](https://arxiv.org/abs/2304.05055)                                                         |         Peking University         |              arXiv              |   2023   |
| [Dynamic Graph Representation Learning with Neural Networks: A Survey](https://arxiv.org/abs/2304.05729)                                                 |    University of Rouen Normandy   |              arXiv              |   2023   |
| [Multiscale Representation Learning for Image Classification: A Survey](https://ieeexplore.ieee.org/abstract/document/9650759)                                                |         Xidian University         |             IEEE TAI            |   2023   |
| [A Survey on Protein Representation Learning: Retrospect and Prospect](https://arxiv.org/abs/2301.00813)      |        Westlake University        |              arXiv              |   2023   |


## Research Papers (Latest Update: NeurIPS 2023)

### Neural Network Architecture-based Approaches
> This group of studies focus on designing and modifying of ...

### Learning-based Approaches
> This group of studies focus on objective function based on ...

### Data-Centric Approaches
> In this group, we categorize the methods that focus on finding a new way to enhance the usefulness of the training data at hand. Data-centric approaches prioritize engineering the data itself rather than focusing on model architecture and loss function design. We categorize data-centric approaches into three techniques: data augmentation, decomposition and transformation, and sample selection.

#### Data Augmentation

#### Decomposition and Transformation

#### Sample Selection


## Neighbor Repositories
- https://github.com/qingsongedu/awesome-AI-for-time-series-papers
- https://github.com/qianlima-lab/time-series-ptms
- https://github.com/qingsongedu/time-series-transformers-review				
- https://github.com/lixus7/Time-Series-Works-Conferences				
- https://github.com/qingsongedu/Awesome-TimeSeries-AIOps-LM-LLM
- https://github.com/qingsongedu/Awesome-SSL4TS
