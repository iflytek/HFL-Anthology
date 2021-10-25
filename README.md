# HFL Anthology
Collections of resources from Joint Laboratory of HIT and iFLYTEK Research (HFL).

<!-- TOC -->

- [Pre-trained Language Models](#Pre-trained-Language-Models)
- [Dataset](#Dataset)
- [Toolkit](#Toolkit)
- [Demo](#Demo)
- [Evaluation Campaign](#Evaluation-Campaign)
- [Paper](#Paper)

<!-- /TOC -->

## Pre-trained Language Models

| Name | Description |
| :------ | :------ |
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
| :------ | :------: | :------: |
| [TextBrewer](https://github.com/airaria/TextBrewer) | Knowledge Distillation for NLP | [Yang et al., 2020](https://arxiv.org/abs/2002.12620) |

## Demo

| Name | Description | Paper |
| :------ | :------: | :------: |
| [iFLYChecker](http://check.hfl-rc.com) | A Chinese Grammar Checking System | - |
| [IFlyLegal](https://github.com/china-ai-law-challenge/CAIL2019/tree/master/阅读理解#法小飞) | A Chinese Legal System for Consultation & Law Searching | [Wang et al., 2019](https://www.aclweb.org/anthology/D19-3017/) |


## Evaluation Campaign

| Name | Description |
| :------ | :------: |
| [CAIL 2020](http://cail.cipsc.org.cn) | Judiciary Reading Comprehension |
| [CMRC 2019](http://hfl-rc.github.io/cmrc2019/) | Sentence Cloze Reading Comprehension |
| [CAIL 2019](http://cail.cipsc.org.cn) | Judiciary Reading Comprehension |
| [CMRC 2018](http://hfl-rc.github.io/cmrc2018/) | Span-Extraction Reading Comprehension |
| [CMRC 2017](http://hfl-rc.github.io/cmrc2017/) | Cloze-style Reading Comprehension |

## Paper

| Paper | Authors | Venue | Note |
| :------ | :------ | :------: | :------: |
| [ExpMRC: Explainability Evaluation for Machine Reading Comprehension](https://arxiv.org/abs/2105.04126) | Yiming Cui, Ting Liu, Wanxiang Che, Zhigang Chen, Shijin Wang |  | [GitHub](https://github.com/ymcui/expmrc) |
| [Benchmarking Robustness of Machine Reading Comprehension Models](https://arxiv.org/abs/2004.14004) | Chenglei Si, Ziqing Yang, Yiming Cui, Wentao Ma, Ting Liu, Shijin Wang | Findings of ACL 2021 | [GitHub](https://github.com/NoviScl/AdvRACE) |
| [A Sentence Cloze Dataset for Chinese Machine Reading Comprehension](https://arxiv.org/abs/2004.03116) | Yiming Cui, Ting Liu, Ziqing Yang, Zhipeng Chen, Wentao Ma, Wanxiang Che, Shijin Wang, Guoping Hu | COLING 2020 | [GitHub](http://hfl-rc.github.io/cmrc2019/) |
| [CharBERT: Character-aware Pre-trained Language Model](https://arxiv.org/abs/2011.01513) | Wentao Ma, Yiming Cui, Chenglei Si, Ting Liu, Shijin Wang, Guoping Hu | COLING 2020 | [GitHub](https://github.com/wtma/CharBERT) |
| [Revisiting Pre-Trained Models for Chinese Natural Language Processing](https://arxiv.org/abs/2004.13922) | Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Shijin Wang, Guoping Hu | Findings of EMNLP 2020 | [GitHub](https://github.com/ymcui/MacBERT) |
| [Is Graph Structure Necessary for Multi-hop Question Answering?](https://arxiv.org/abs/2004.03096) | Nan Shao, Yiming Cui, Ting Liu, Shijin Wang, Guoping Hu | EMNLP 2020 | - |
| [TextBrewer: An Open-Source Knowledge Distillation Toolkit for Natural Language Processing](https://www.aclweb.org/anthology/2020.acl-demos.2/) | Ziqing Yang, Yiming Cui, Zhipeng Chen, Wanxiang Che, Ting Liu, Shijin Wang, Guoping Hu | ACL 2020 Demo | [GitHub](https://github.com/airaria/TextBrewer) |
| [Conversational Word Embedding for Retrieval-based Dialog System](https://www.aclweb.org/anthology/2020.acl-main.127/) | Wentao Ma, Yiming Cui, Ting Liu, Dong Wang, Shijin Wang, Guoping Hu | ACL 2020 | [GitHub](https://github.com/wtma/PR-Embedding) |
| [Discriminative Sentence Modeling for Story Ending Prediction](https://aaai.org/ojs/index.php/AAAI/article/view/6260) | Yiming Cui, Wanxiang Che, Wei-Nan Zhang, Ting Liu, Shijin Wang, Guoping Hu | AAAI 2020 | - |
| [Cross-Lingual Machine Reading Comprehension](https://www.aclweb.org/anthology/D19-1169/) | Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Shijin Wang, Guoping Hu | EMNLP 2019 | [GitHub](https://github.com/ymcui/Cross-Lingual-MRC) |
| [A Span-Extraction Dataset for Chinese Machine Reading Comprehension](https://www.aclweb.org/anthology/D19-1600/) | Yiming Cui, Ting Liu, Wanxiang Che, Li Xiao, Zhipeng Chen, Wentao Ma, Shijin Wang, Guoping Hu | EMNLP 2019 | [GitHub](https://github.com/ymcui/cmrc2018) |
| [IFlyLegal: A Chinese Legal System for Consultation, Law Searching, and Document Analysis](https://www.aclweb.org/anthology/D19-3017/) | Ziyue Wang, Baoxin Wang, Xingyi Duan, Dayong Wu, Shijin Wang, Guoping Hu, Ting Liu | EMNLP 2019 Demo | - |
| [TripleNet: Triple Attention Network for Multi-Turn Response Selection in Retrieval-based Chatbots](https://www.aclweb.org/anthology/K19-1069/) | Wentao Ma, Yiming Cui, Nan Shao, Su He, Wei-Nan Zhang, Ting Liu, Shijin Wang, Guoping Hu | CoNLL 2019 | [GitHub](https://github.com/wtma/TripleNet) |
| [Pre-Training with Whole Word Masking for Chinese BERT](https://arxiv.org/abs/1906.08101) | Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Ziqing Yang, Shijin Wang, Guoping Hu | - | [GitHub1](https://github.com/ymcui/Chinese-BERT-wwm/), [GitHub2](https://github.com/ymcui/Chinese-PreTrained-XLNet) |
| [Improving Machine Reading Comprehension via Adversarial Training](https://arxiv.org/abs/1911.03614) | Ziqing Yang, Yiming Cui, Wanxiang Che, Ting Liu, Shijin Wang, Guoping Hu | - | - |
| [Contextual Recurrent Units for Cloze-style Reading Comprehension](https://arxiv.org/abs/1911.05960) | Yiming Cui, Wei-Nan Zhang, Wanxiang Che, Ting Liu, Zhipeng Chen, Shijin Wang, Guoping Hu | - | - |
| [CJRC: A Reliable Human-Annotated Benchmark DataSet for Chinese Judicial Reading Comprehension](https://arxiv.org/abs/1912.09156) | Xingyi Duan, Baoxin Wang, Ziyue Wang, Wentao Ma, Yiming Cui, Dayong Wu, Shijin Wang, Ting Liu, Tianxiang Huo, Zhen Hu, Heng Wang, Zhiyuan Liu | CCL 2019 | [GitHub](https://github.com/china-ai-law-challenge/CAIL2019) |
| [Convolutional Spatial Attention Model for Reading Comprehension with Multiple-Choice Questions](https://arxiv.org/abs/1811.08610) | Zhipeng Chen, Yiming Cui, Wentao Ma, Shijin Wang, Guoping Hu | AAAI 2019 | - |
| [Disconnected Recurrent Neural Networks for Text Categorization](https://www.aclweb.org/anthology/P18-1215/) | Baoxin Wang | ACL 2018 | - |
| [HFL-RC System at SemEval-2018 Task 11: Hybrid Multi-Aspects Model for Commonsense Reading Comprehension](https://arxiv.org/abs/1803.05655) | Zhipeng Chen, Yiming Cui*, Wentao Ma, Shijin Wang, Ting Liu, Guoping Hu | - | - |
| [Dataset for the First Evaluation on Chinese Machine Reading Comprehension](https://www.aclweb.org/anthology/L18-1431/) | Yiming Cui, Ting Liu, Zhipeng Chen, Wentao Ma, Shijin Wang, Guoping Hu | LREC 2018 | [GitHub](https://github.com/ymcui/cmrc2017) |
| [Chinese Grammatical Error Diagnosis using Statistical and Prior Knowledge driven Features with Probabilistic Ensemble Enhancement](https://www.aclweb.org/anthology/W18-3707/) | Ruiji Fu, Zhengqi Pei, Jiefu Gong, Wei Song, Dechuan Teng, Wanxiang Che, Shijin Wang, Guoping Hu, Ting Liu | NLP-TEA@ACL 2018 | - |
| [面向作文自动评分的优美句识别](http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=2586) | 付瑞吉，王栋，王士进，胡国平，刘挺 | 中文信息学报 | - |
| [Attention-over-Attention Neural Networks for Reading Comprehension](https://www.aclweb.org/anthology/P17-1055/) | Yiming Cui, Zhipeng Chen, Si Wei, Shijin Wang, Ting Liu, Guoping Hu | ACL 2017 | - |
| [Generating and Exploiting Large-scale Pseudo Training Data for Zero Pronoun Resolution](https://www.aclweb.org/anthology/P17-1010/) | Ting Liu, Yiming Cui, Qingyu Yin, Wei-Nan Zhang, Shijin Wang, Guoping Hu | ACL 2017 | - |
| [Consensus Attention-based Neural Networks for Chinese Reading Comprehension](https://www.aclweb.org/anthology/C16-1167/) | Yiming Cui, Ting Liu, Zhipeng Chen, Shijin Wang, Guoping Hu | COLING 2016 | [GitHub](https://github.com/ymcui/Chinese-Cloze-RC) |
| [LSTM Neural Reordering Feature for Statistical Machine Translation](https://www.aclweb.org/anthology/N16-1112/) | Yiming Cui, Shijin Wang, Jianfeng Li | NAACL 2016 | - |



## Follow Us
Follow our official WeChat account to keep updated with our latest technologies!

![](./hfl_qrcode.jpg)

