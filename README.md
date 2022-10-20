
<p>
<a href="https://console.tiyaro.ai/explore?q=hfl/&pub=hfl"> <img src="https://tiyaro-public-docs.s3.us-west-2.amazonaws.com/assets/try_on_tiyaro_badge.svg"></a>
</p>

[**中文**](https://github.com/ymcui/HFL-Anthology/blob/master/README_ZH.md) | [**English**](https://github.com/ymcui/HFL-Anthology)

<p align="center">
    <br>
    <img src="./banner.png" width="500"/>
    <br>
</p>


Collections of resources from Joint Laboratory of HIT and iFLYTEK Research (HFL).

<!-- TOC -->

- [Pre-trained Language Models](#Pre-trained-Language-Models)
- [Dataset](#Dataset)
- [Toolkit](#Toolkit)
- [Demo](#System-Demonstration)
- [Evaluation Campaign](#Evaluation-Campaign)
- [Paper](#Paper)

<!-- /TOC -->

## Pre-trained Language Model

| Name | Description |
| :------ | :------ |
| [PERT](https://github.com/ymcui/PERT) | Chinese and English PERT models (base-level, large-level) |
| [Chinese-MobileBERT](https://github.com/ymcui/Chinese-MobileBERT) | Chinese MobileBERT (base-level, large-level) *(archival purpose only)* |
| [CINO](https://github.com/ymcui/Chinese-Minority-PLM) | Pre-trained Language Models for Chinese Minority Languages |
| [MacBERT](https://github.com/ymcui/MacBERT) | Chinese pre-trained MacBERT models (MacBERT-base, MacBERT-large) |
| [CharBERT](https://github.com/wtma/CharBERT) | English pre-trained CharBERT models |
| [Chinese-ELECTRA](https://github.com/ymcui/Chinese-ELECTRA) | Chinese pre-trained ELECTRA models (ELECTRA-base, ELECTRA-small) with code supports for six tasks: CMRC 2018, DRCD, XNLI, ChnSentiCorp, LCQMC, BQCorpus |
| [Chinese-XLNet](https://github.com/ymcui/Chinese-XLNet) | Chinese pre-trained XLNet models: XLNet-mid, XLNet-base |
| [Chinese-BERT-wwm](https://github.com/ymcui/Chinese-BERT-wwm) | Chinese BERT with Whole Word Masking (wwm), including BERT-wwm, BERT-wwm-ext, RoBERTa-wwm-ext, RoBERTa-wwm-ext-large, RBT3, RBTL3 |


## Dataset

| Name | Type | Paper |
| :------ | :------: | :------: |
| [ExpMRC](https://github.com/ymcui/expmrc) | Reading Comprehension | [Cui et al., 2021](https://arxiv.org/abs/2105.04126) |
| [AdvRACE](https://github.com/NoviScl/AdvRACE) | Reading Comprehension | [Si et al., 2020](https://arxiv.org/abs/2004.14004) |
| [CMRC 2019](https://github.com/ymcui/cmrc2019) | Reading Comprehension | [Cui et al., 2020](https://arxiv.org/abs/2004.03116) |
| [CJRC](https://github.com/china-ai-law-challenge/CAIL2019/tree/master/阅读理解) | Reading Comprehension | [Duan et al., 2019](https://arxiv.org/abs/1912.09156) |
| [CMRC 2018](https://github.com/ymcui/cmrc2018) | Reading Comprehension | [Cui et al., 2019](https://www.aclweb.org/anthology/D19-1600/) |
| [CMRC 2017](https://github.com/ymcui/cmrc2017) | Reading Comprehension | [Cui et al., 2018](https://www.aclweb.org/anthology/L18-1431/) |
| [PD&CFT](https://github.com/ymcui/Chinese-Cloze-RC) | Reading Comprehension | [Cui et al., 2016](https://www.aclweb.org/anthology/C16-1167/) |


## Toolkit

| Name | Description | Paper |
| :------ | :------- | :------: |
| [TextPruner](https://github.com/airaria/TextPruner) | Model Pruning for NLP | [Yang et al., 2022](https://aclanthology.org/2022.acl-demo.4) |
| [TextBrewer](https://github.com/airaria/TextBrewer) | Knowledge Distillation for NLP | [Yang et al., 2020](https://aclanthology.org/2020.acl-demos.2/) |


## System Demonstration

| Name | Description | Paper |
| :------ | :------- | :------: |
| IFlyEA | A Chinese Essay Assessment System with Automated Rating, Review Generation, and Recommendation | [Gong et al., 2021](https://aclanthology.org/2021.acl-demo.29/) |
| [iFLYChecker](http://check.hfl-rc.com) | A Chinese Grammar Checking System | - |
| [IFlyLegal](https://github.com/china-ai-law-challenge/CAIL2019/tree/master/阅读理解#法小飞) | A Chinese Legal System for Consultation & Law Searching | [Wang et al., 2019](https://www.aclweb.org/anthology/D19-3017/) |


## Evaluation Campaign

| Name | Description | Live Leaderboard |
| :------ | :------: | :------: |
| [CMRC 2022](http://cmrc2022.hfl-rc.com) | Explainable Reading Comprehension | ✅ |
| [CTC 2021](https://github.com/destwang/CTC2021) | Chinese Text Correction | ✅ |
| [CAIL 2020](http://cail.cipsc.org.cn) | Judiciary Reading Comprehension | ❌ |
| [CMRC 2019](http://hfl-rc.github.io/cmrc2019/) | Sentence Cloze Reading Comprehension | ✅ |
| [CAIL 2019](http://cail.cipsc.org.cn) | Judiciary Reading Comprehension | ❌ |
| [CMRC 2018](http://hfl-rc.github.io/cmrc2018/) | Span-Extraction Reading Comprehension | ✅ |
| [CMRC 2017](http://hfl-rc.github.io/cmrc2017/) | Cloze-style Reading Comprehension | ❌ |

## Paper

| Year | Paper | Author List | Published in | Note |
| :-----: | :------ | :------- | :------: | :------: |
| 2022 | [Visualizing Attention Zones in Machine Reading Comprehension Models](https://star-protocols.cell.com/protocols/1736) | Yiming Cui, Wei-Nan Zhang, Ting Liu | STAR Protocols | [GitHub](https://github.com/ymcui/mrc-model-analysis) |
| 2022 | [Multilingual Multi-Aspect Explainability Analyses on Machine Reading Comprehension Models](https://www.cell.com/iscience/fulltext/S2589-0042%2822%2900446-1) | Yiming Cui, Wei-Nan Zhang, Wanxiang Che, Ting Liu, Zhigang Chen, Shijin Wang | iScience | [GitHub](https://github.com/ymcui/mrc-model-analysis) |
| 2021 | [ExpMRC: Explainability Evaluation for Machine Reading Comprehension](https://www.cell.com/heliyon/fulltext/S2405-8440%2822%2900578-3) | Yiming Cui, Ting Liu, Wanxiang Che, Zhigang Chen, Shijin Wang | Heliyon | [GitHub](https://github.com/ymcui/expmrc) |
| 2022 | [Teaching Machines to Read, Answer and Explain](https://ieeexplore.ieee.org/document/9729502) | Yiming Cui, Ting Liu, Wanxiang Che, Zhigang Chen, Shijin Wang | IEEE/ACM TASLP |  |
| 2022 | [PERT: Pre-training BERT with Permuted Language Model](https://arxiv.org/abs/2203.06906) | Yiming Cui, Ziqing Yang, Ting Liu | | [GitHub](https://github.com/ymcui/PERT) |
| 2022 | [A Static and Dynamic Attention Framework for Multi Turn Dialogue Generation](https://dl.acm.org/doi/10.1145/3522763) | Wei-Nan Zhang, Yiming Cui, Kaiyan Zhang, Yifa Wang, Qingfu Zhu, Lingzhi Li, Ting Liu | ACM TOIS |  |
| 2022 | [Cross-Lingual Text Classification with Multilingual Distillation and Zero-Shot-Aware Training](https://arxiv.org/abs/2202.13654) | Ziqing Yang, Yiming Cui, Zhigang Chen, Shijin Wang | | |
| 2022 | [CINO: A Chinese Minority Pre-trained Language Model](https://arxiv.org/abs/2202.13558) | Ziqing Yang, Zihang Xu, Yiming Cui, Baoxin Wang, Min Lin, Dayong Wu, Zhigang Chen | [GitHub](https://github.com/ymcui/Chinese-Minority-PLM) |
| 2022 | [HFL at SemEval-2022 Task 8: A Linguistics-inspired Regression Model with Data Augmentation for Multilingual News Similarity](https://aclanthology.org/2022.semeval-1.157/) | Zihang Xu, Ziqing Yang, Yiming Cui, Zhigang Chen | SemEval 2022 | [GitHub](https://github.com/GeekDream-x/SemEval2022-Task8-TonyX) |
| 2022 | [HIT at SemEval-2022 Task 2: Pre-trained Language Model for Idioms Detection](https://aclanthology.org/2022.semeval-1.28/) | Zheng Chu, Ziqing Yang, Yiming Cui, Zhigang Chen, Ming Liu | SemEval 2022 | |
| 2022 | [TextPruner: A Model Pruning Toolkit for Pre-trained Language Models](https://aclanthology.org/2022.acl-demo.4) | Ziqing Yang, Yiming Cui, Zhigang Chen | ACL 2022 Demo | [GitHub](https://github.com/airaria/TextPruner)
| 2022 | [Interactive Gated Decoder for Machine Reading Comprehension](https://dl.acm.org/doi/10.1145/3501399) | Yiming Cui, Wanxiang Che, Ziqing Yang, Ting Liu, Bing Qin, Shijin Wang, Guoping Hu | ACM TALLIP |  |
| 2021 | [IFlyEA: A Chinese Essay Assessment System with Automated Rating, Review Generation, and Recommendation](https://aclanthology.org/2021.acl-demo.29/) | Jiefu Gong, Xiao Hu, Wei Song, Ruiji Fu, Zhichao Sheng, Bo Zhu, Shijin Wang, Ting Liu | ACL 2021 Demo |  |
| 2021 | [Dynamic Connected Networks for Chinese Spelling Check](https://aclanthology.org/2021.findings-acl.216/) | Baoxin Wang, Wanxiang Che, Dayong Wu, Shijin Wang, Guoping Hu, Ting Liu | Findings of ACL 2021 | |
| 2021 | [Various Legal Factors Extraction Based on Machine Reading Comprehension](https://link.springer.com/chapter/10.1007/978-3-030-88189-4_2) | Beichen Wang, Ziyue Wang, Baoxin Wang, Dayong Wu, Zhigang Chen, Shijin Wang, Guoping Hu | CCIR 2021 | |
| 2021 | 利用深层语言分析改进中文作文自动评分方法 | 魏思，巩捷甫，宋巍，宋子尧，王士进 | 中文信息学报 | |
| 2021 | [Bilingual Alignment Pre-training for Zero-shot Cross-lingual Transfer](https://aclanthology.org/2021.mrqa-1.10/) | Ziqing Yang, Wentao Ma, Yiming Cui, Jiani Ye, Wanxiang Che, Shijin Wang | MRQA 2021 |  |
| 2021 | [Adversarial Training for Machine Reading Comprehension with Virtual Embeddings](https://aclanthology.org/2021.starsem-1.30/) | Ziqing Yang, Yiming Cui, Chenglei Si, Wanxiang Che, Ting Liu, Shijin Wang, Guoping Hu | *SEM 2021 |  |
| 2021 | [Pre-Training with Whole Word Masking for Chinese BERT](http://ieeexplore.ieee.org/document/9599397) | Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Ziqing Yang | IEEE/ACM TASLP | [GitHub1](https://github.com/ymcui/Chinese-BERT-wwm/), [GitHub2](https://github.com/ymcui/Chinese-PreTrained-XLNet) |
| 2021 | [Benchmarking Robustness of Machine Reading Comprehension Models](https://arxiv.org/abs/2004.14004) | Chenglei Si, Ziqing Yang, Yiming Cui, Wentao Ma, Ting Liu, Shijin Wang | Findings of ACL 2021 | [GitHub](https://github.com/NoviScl/AdvRACE) |
| 2020 | [A Sentence Cloze Dataset for Chinese Machine Reading Comprehension](https://arxiv.org/abs/2004.03116) | Yiming Cui, Ting Liu, Ziqing Yang, Zhipeng Chen, Wentao Ma, Wanxiang Che, Shijin Wang, Guoping Hu | COLING 2020 | [GitHub](http://hfl-rc.github.io/cmrc2019/) |
| 2020 | [CharBERT: Character-aware Pre-trained Language Model](https://arxiv.org/abs/2011.01513) | Wentao Ma, Yiming Cui, Chenglei Si, Ting Liu, Shijin Wang, Guoping Hu | COLING 2020 | [GitHub](https://github.com/wtma/CharBERT) |
| 2020 | [Revisiting Pre-Trained Models for Chinese Natural Language Processing](https://arxiv.org/abs/2004.13922) | Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Shijin Wang, Guoping Hu | Findings of EMNLP 2020 | [GitHub](https://github.com/ymcui/MacBERT) |
| 2020 | [Is Graph Structure Necessary for Multi-hop Question Answering?](https://arxiv.org/abs/2004.03096) | Nan Shao, Yiming Cui, Ting Liu, Shijin Wang, Guoping Hu | EMNLP 2020 | - |
| 2020 | [TextBrewer: An Open-Source Knowledge Distillation Toolkit for Natural Language Processing](https://www.aclweb.org/anthology/2020.acl-demos.2/) | Ziqing Yang, Yiming Cui, Zhipeng Chen, Wanxiang Che, Ting Liu, Shijin Wang, Guoping Hu | ACL 2020 Demo | [GitHub](https://github.com/airaria/TextBrewer) |
| 2020 | [Conversational Word Embedding for Retrieval-based Dialog System](https://www.aclweb.org/anthology/2020.acl-main.127/) | Wentao Ma, Yiming Cui, Ting Liu, Dong Wang, Shijin Wang, Guoping Hu | ACL 2020 | [GitHub](https://github.com/wtma/PR-Embedding) |
| 2020 | [Discriminative Sentence Modeling for Story Ending Prediction](https://aaai.org/ojs/index.php/AAAI/article/view/6260) | Yiming Cui, Wanxiang Che, Wei-Nan Zhang, Ting Liu, Shijin Wang, Guoping Hu | AAAI 2020 | - |
| 2019 | [Cross-Lingual Machine Reading Comprehension](https://www.aclweb.org/anthology/D19-1169/) | Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Shijin Wang, Guoping Hu | EMNLP 2019 | [GitHub](https://github.com/ymcui/Cross-Lingual-MRC) |
| 2019 | [A Span-Extraction Dataset for Chinese Machine Reading Comprehension](https://www.aclweb.org/anthology/D19-1600/) | Yiming Cui, Ting Liu, Wanxiang Che, Li Xiao, Zhipeng Chen, Wentao Ma, Shijin Wang, Guoping Hu | EMNLP 2019 | [GitHub](https://github.com/ymcui/cmrc2018) |
| 2019 | [IFlyLegal: A Chinese Legal System for Consultation, Law Searching, and Document Analysis](https://www.aclweb.org/anthology/D19-3017/) | Ziyue Wang, Baoxin Wang, Xingyi Duan, Dayong Wu, Shijin Wang, Guoping Hu, Ting Liu | EMNLP 2019 Demo | - |
| 2019 | [TripleNet: Triple Attention Network for Multi-Turn Response Selection in Retrieval-based Chatbots](https://www.aclweb.org/anthology/K19-1069/) | Wentao Ma, Yiming Cui, Nan Shao, Su He, Wei-Nan Zhang, Ting Liu, Shijin Wang, Guoping Hu | CoNLL 2019 | [GitHub](https://github.com/wtma/TripleNet) |
| 2019 | [Improving Machine Reading Comprehension via Adversarial Training](https://arxiv.org/abs/1911.03614) | Ziqing Yang, Yiming Cui, Wanxiang Che, Ting Liu, Shijin Wang, Guoping Hu | - | - |
| 2019 | [Contextual Recurrent Units for Cloze-style Reading Comprehension](https://arxiv.org/abs/1911.05960) | Yiming Cui, Wei-Nan Zhang, Wanxiang Che, Ting Liu, Zhipeng Chen, Shijin Wang, Guoping Hu | - | - |
| 2019 | [CJRC: A Reliable Human-Annotated Benchmark DataSet for Chinese Judicial Reading Comprehension](https://arxiv.org/abs/1912.09156) | Xingyi Duan, Baoxin Wang, Ziyue Wang, Wentao Ma, Yiming Cui, Dayong Wu, Shijin Wang, Ting Liu, Tianxiang Huo, Zhen Hu, Heng Wang, Zhiyuan Liu | CCL 2019 | [GitHub](https://github.com/china-ai-law-challenge/CAIL2019) |
| 2019 | [Convolutional Spatial Attention Model for Reading Comprehension with Multiple-Choice Questions](https://arxiv.org/abs/1811.08610) | Zhipeng Chen, Yiming Cui, Wentao Ma, Shijin Wang, Guoping Hu | AAAI 2019 | - |
| 2018 | [Disconnected Recurrent Neural Networks for Text Categorization](https://www.aclweb.org/anthology/P18-1215/) | Baoxin Wang | ACL 2018 | - |
| 2018 | [HFL-RC System at SemEval-2018 Task 11: Hybrid Multi-Aspects Model for Commonsense Reading Comprehension](https://arxiv.org/abs/1803.05655) | Zhipeng Chen, Yiming Cui*, Wentao Ma, Shijin Wang, Ting Liu, Guoping Hu | - | - |
| 2018 | [Dataset for the First Evaluation on Chinese Machine Reading Comprehension](https://www.aclweb.org/anthology/L18-1431/) | Yiming Cui, Ting Liu, Zhipeng Chen, Wentao Ma, Shijin Wang, Guoping Hu | LREC 2018 | [GitHub](https://github.com/ymcui/cmrc2017) |
| 2018 | [Chinese Grammatical Error Diagnosis using Statistical and Prior Knowledge driven Features with Probabilistic Ensemble Enhancement](https://www.aclweb.org/anthology/W18-3707/) | Ruiji Fu, Zhengqi Pei, Jiefu Gong, Wei Song, Dechuan Teng, Wanxiang Che, Shijin Wang, Guoping Hu, Ting Liu | NLP-TEA@ACL 2018 | - |
| 2017 | [面向作文自动评分的优美句识别](http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=2586) | 付瑞吉，王栋，王士进，胡国平，刘挺 | 中文信息学报 | - |
| 2017 | [Attention-over-Attention Neural Networks for Reading Comprehension](https://www.aclweb.org/anthology/P17-1055/) | Yiming Cui, Zhipeng Chen, Si Wei, Shijin Wang, Ting Liu, Guoping Hu | ACL 2017 | - |
| 2017 | [Generating and Exploiting Large-scale Pseudo Training Data for Zero Pronoun Resolution](https://www.aclweb.org/anthology/P17-1010/) | Ting Liu, Yiming Cui, Qingyu Yin, Wei-Nan Zhang, Shijin Wang, Guoping Hu | ACL 2017 | - |
| 2016 | [Consensus Attention-based Neural Networks for Chinese Reading Comprehension](https://www.aclweb.org/anthology/C16-1167/) | Yiming Cui, Ting Liu, Zhipeng Chen, Shijin Wang, Guoping Hu | COLING 2016 | [GitHub](https://github.com/ymcui/Chinese-Cloze-RC) |
| 2016 | [LSTM Neural Reordering Feature for Statistical Machine Translation](https://www.aclweb.org/anthology/N16-1112/) | Yiming Cui, Shijin Wang, Jianfeng Li | NAACL 2016 | - |

## Follow Us
Follow our official WeChat account to keep updated with our latest technologies!

![](./hfl_qrcode.jpg)

