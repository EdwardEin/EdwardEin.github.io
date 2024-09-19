---

layout: post 

title: "Bioinformatics" 

date: 2024-09-19 

categories: jekyll update 

---

# Study Plan

1. **Before-class Learning** (1hr each week)
   * Bioinformatics tutorial
2. **In-class Learning** (1.5hr each week)
   * Take notes
   * Practice
   * Ask questions
3. **After-class Learning** (3hrs each week)
   * Review the lecture content
   * Self-learning and practicing
   * Group study

# 0. Introduction and Getting Started

> Bioinformatics: _Decode the Language of Life_

## 1. Introduction

### **4** steps of Bioinformatics:

* **Question**: Biological/Medical Knowledge
  * What is the universe made of?
  * <font color=red>What is the biological basis of consciousness?</font>
  * <font color=red>Why do humans have so few genes?</font>
  * <font color=red>To what extent are genetic variation and personal health linked?</font>
  * Can the laws of physics be unified?

* **Information**: Biological/Medical Data
  * Images
  * Sequences
    * _Moore's Law_ : Revolution of Sequencing Power
    * Type of <mark>NGS</mark> (Next Generation Sequencing)
      1. DNA-seq
      2. RNA-seq
      3. Epigenetics
         * DNAase
         * Methylation
         * Histone modifications: ChiP-seq
      4. Interaction
         * Protein-DNA: ChiP-seq
         * Protein-RNA: CLIP-seq
         * DNA-RNA: Grid-seq

* **Analysis**: Data Clean & Feature Extraction

  | Variation                   | Sequencing Methods                  | Bioinformatics Tools                                         |
  | --------------------------- | ----------------------------------- | ------------------------------------------------------------ |
  | **Abundance**               | RNA-seq                             | DESeq2, EdgeR, Cufflinks                                     |
  | **Splicing**                | RNA-seq                             | rMATs, TOPHAT/Cufflinks                                      |
  | **Editing**                 | RNA-seq                             | GIREMI, REDltools, SPRINT                                    |
  | **APA**                     | RNA-seq/PAT-seq                     | DaPars, APAtrap                                              |
  | **Translation**             | Ribo-seq                            | <font color=red>RiboWave</font>, RiboTaper, ORFscore         |
  | **Degradation**             | Degradome-Seq (PARE-seq), cfRNA-seq | sPARTA, <font color=red>cfPeak</font>                        |
  | **Modification**            | m6A-seq, MeRIP-seq, miCLIP          | m6aViewer, MeRIP-PF                                          |
  | **Structure**               | isSHAPE, SHAPE-map, DMS-seq         | <font color=red>RNAstructure</font>, RNAfold, <font color=red>RME</font> |
  | **RNA-protein interaction** | HITS-CLIP, PAR-CLIP, iCLIP, eCLIP   | Piranha, PARalyzer, CIMS; <font color=red>POSTAR/CLIPdb</font> |

* **Modeling**: Probabilistic Model & Computational Algorithm
  * Machine Learning Models
    1. Linear Regression
    2. Logistic Regression
    3. DIscriminant Analysis
    4. Decision Tree
    5. Random Forest
    6. Support Vector Machine
    7. Deep Learning
    8. Naive Bayes
    9. K-nearest neighbor
    10. Hidden Markov model
    11. Genetic Algorithm

>An **algorithm** and a **model** are both important concepts in computer science and machine learning, but they serve different purposes:
>
>1. **Algorithm**:
>   An algorithm is a step-by-step procedure or set of rules used to solve a problem or perform a task. It’s a defined series of operations or instructions that can process data to produce an output. Algorithms are the logic or the processes behind a program.
>2. **Model**:
>   A model is the output or the representation that results from applying an algorithm to data. In machine learning, a model represents the learned patterns or relationships in data that are used to make predictions or decisions.



