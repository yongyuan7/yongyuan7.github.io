---
permalink: /markdown/
title: "Bioinformatics Collaboration"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Introduction

* Microbiome sequencing price has dropped substantially, more researchers and companies are interested in learning microbiome in human, environment, and animals. Shotgun sequencing has enabled in depth learning of microbial community structure, pathway, functional potential, and active functions. One answer we ALL want to know about microbiome: Who is there, what are they doing? 
* Shotgun data is easier to obtain now than before with highthrougput sequencing platforms like Illumina NovaSeq6000. However, it is challenging to analyze the data for researchers who doesn't have coding experiences. First, the data generated from shotgun is huge, usually ranges from 3G to 20G, more than 40 million reads per sample for shotgun metagenome. Shotgun metatreanscriptome is even more challenging, with more than 20G and 100 million reads per sample. The mid-files generated in computation will multiply output size. It's easy to have 100 samples metagenome take 4T of storage space. Second, because of large data, computation time can exponentially increase. For example, shotgun metagenome assembly and mapping can take up to 20 hours per sample. Shotgun metatranscriptome QC rRNA, adapter, human genome removal can take up to 30 hours computation time. The computation also consums large memory(100G). Third, data processing is time consuming and requires the access to supercomputing cluster (HPC) or HPC cloud. Finally, data processing also involves proficient use of python and unix in Linux system.
* I am happy to collaborate on your microbiome projects. I can offer my insights on what computation resources you need and help you process the data with potential options. If you are a student, I am happy to guide you on how to learn those bioinformatic tools and pipelines. Please email me for collaborations. 


### Typical Microbiome Sequencing

| Sequencing         | Typical steps                                                             |
| --------         | ------------------------------------------------------------ |
| Shotgun metagenome| QC, host removal(if needed), mapping or assembly, species and pathway profiling, and more |
| Shotgun metatranscriptome| QC, rRNA removal, host removal (if needed) mapping or assembly, gene expression, and more |
| Amplicon sequencing| QC, OTU table, alpha and beta diversity, community structure|

## 介绍
* 微生物组测序价格有显著的降低，越来越多的科研工作人员和公司对微生物组学有很大的兴趣。宏基因组和宏转录组可以给我们对微生物组群有更加深入的认识，包括微生物组群的结构，功能路径，和基因表达。一个对微生物组学有兴趣的人都想知道的是-是谁在这个样品里，他们在做什么？
* 宏基因组的数据比以前更加容易获得，得益于一代又一代高通量测序机器比如Illumina NovaSeq6000。但是宏基因组的数据很大，一般一个样品就有3G-20G，40 million reads。一个项目很容易就会有几个T的数据要处理。宏转录组更加有挑战，一个样品可以多到20G，100 million reads以上的数据量。宏基因组的mapping 和assembly 会花很长时间，很常见的要20个小时一个样。宏转录组更加花计算时间，一个简单的质控去除各种rRNA, adapters, host reads可以花到30个小时，这些计算对内存要求也很高，很轻松就会要100G 的内存，中间文件的存储量更是达到了原始数据的几倍。数据处理花时间，需要在超级计算机，或者云计算（亚马云，阿里云)。计算对科研人员也有编程要求，需要会在Linux 系统里熟练用python，unix。
* 我愿意参与和合作您的有意思的微生物组学的项目。我可以指导您让您了解项目需要什么计算资源和引导您处理测序的raw data几种选择。如果您是学生，对微生物组学有兴趣。我愿意教您去找什么资源，怎么一步步去学习生物信息学，到可以自己掌握和熟练应用。有兴趣的合作者可以发我邮件。


### 常见的微生物组学测序

| 测序种类          | 常见步骤                                                            |
| --------         | ------------------------------------------------------------ |
| 宏基因组测序| QC, mapping or assembly, species and pathway profiling, and more |
| 宏转录组测序| QC, rRNA removal, mapping or assembly, gene expression, and more |
| 扩增子测序| QC, OTU table, alpha and beta diversity, community structure|


