# 生物信息学学习记录 - Week1



### 1. Week 1 课堂笔记



#### 1.1 算法(Algorithm)与模型(Model)的区别

在生物信息学中，*算法 Algorithm* 和 *模型 Model是* 两个核心概念，它们在数据分析和问题求解中扮演不同的角色。

- **算法：** 用于解决特定问题的方法（一系列明确定义的指令或步骤）。例如，BLAST（Basic Local Alignment Search Tool）是一种用于序列比对的算法，它按照特定的计算流程搜索相似的序列。
- **模型：** 是对现实世界数据的数学或计算机表示，通常用于预测或解释生物现象。例如，Hidden Markov Model（HMM）是一种用于基因注释的统计模型。

    |      | 算法（Algorithm）           | 模型（Model）            |
    | ---- | --------------------------- | ------------------------ |
    | 定义 | 解决数学问题的方法          | 实际问题转化成的数学问题 |
    | 作用 | 计算、搜索、优化等          | 预测、分类、解释数据     |
    | 例子 | BLAST、Needleman-Wunsch算法 | HMM、神经网络            |



#### 1.2 下一代测序技术(Next Generation Sequencing Technology)

  1. ﻿﻿﻿DNA-seq
  2. ﻿﻿﻿RNA-seq
  3. ﻿﻿﻿Epigenetics
     * DNAase
     * ﻿﻿Methylation
     * Histone modifications: ChlP-seq
  4. Interaction
     * ﻿﻿Protein-DNA: ChIP-seq
     * Protein-RNA: CLIP-seq
     * ﻿﻿DNA-RNA: Grid-seq

     

#### 1.3  Steps of Bioinfomatics

研究问题的一般步骤：Question、Information、Analysis、Modeling

  * **Question：** Biological/Medical Knowledge
  * **Information:** Biological/Medical Data
  * **Analysis:** Data Clean & Feature Extraction
  * **Modeling:** Probabilistic  Model & Computation Algorithm

对于Question/Hypothesis-driven Science: Question -> Information -> Analysis -> Modeling

对于Big Data-driven Science: Information -> Analysis -> Modeling -> Question


---



### 2. 生物信息学学习计划



#### 学习目标

- 掌握生物信息学的基本概念和方法。
- 熟悉常见的生物数据分析工具和编程语言（如Python和R）
- 理解基因组学、蛋白质组学和系统生物学中的主要算法和模型
- 能够使用实际数据集进行生物信息学分析

#### 学习计划

  | 周数      | 学习内容                                 |
  | --------- | ---------------------------------------- |
  | 第1-4周   | 生物信息学基础概念，Linux基础操作        |
  | 第5-12周  | NGS数据分析（RNA-Seq, ChIP-Seq, GWAS等） |
  | 第13-16周 | Machine Learning & AI                    |

#### 学习资源

- **编程语言**：Python（Biopython）、R（Bioconductor）
- **数据库**：NCBI、ENSEMBL、UCSC Genome Browser
- **分析工具**：BLAST、Bowtie、GATK、TensorFlow（用于深度学习）
