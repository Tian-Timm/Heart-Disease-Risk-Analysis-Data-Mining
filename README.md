# 🫀 Heart Disease Risk Analysis & Data Mining (2022 BRFSS) | 基于 2022 BRFSS 数据的心脏病风险分析与挖掘

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Data Science](https://img.shields.io/badge/Data-Science-orange.svg)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green.svg)

## 📖 Project Overview | 项目简介
This project analyzes the **2022 Behavioral Risk Factor Surveillance System (BRFSS)** dataset to predict heart disease risk. It implements a complete data science pipeline, including rigorous preprocessing, statistical correlation analysis, multi-model classification, and association rule mining.

本项目基于美国 CDC 的 **2022 年行为风险因素监测系统 (BRFSS)** 数据集进行心脏病风险预测。项目实现了完整的数据科学流程：包括严格的数据预处理、统计相关性分析、多模型分类实验以及关联规则挖掘。

## 📊 Data Source | 数据来源
* **Dataset Name**: Indicators of Heart Disease (2022 BRFSS)
* **Link**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data)
* **Description**: This is a major behavioral health survey conducted annually by the CDC.
* **说明**: 数据来源于 CDC 每年进行的重大行为健康调查，可从 Kaggle 获取。

---

## ✨ Key Highlights | 项目亮点

### 1. Precise Data Cleaning | 精细化数据清洗
* **EN**: Conducted deduplication and handled outliers for numerical variables (BMI, SleepTime, etc.) using the **IQR method** combined with medical logic. Performed **Ordinal Encoding** and **Binary Mapping** for 30+ categorical features.
* **CN**: 对数据进行了去重处理，并结合 **IQR 方法**与医学逻辑对数值变量（BMI、睡眠时间等）进行异常值剔除。对 30 多个分类变量进行了**有序编码**及**二值化转换**。

### 2. Statistical Evidence | 严谨的统计检验
* **EN**: Evaluated feature importance using **Chi-square tests** (for categorical) and **Pearson correlation** (for numerical) to scientifically select predictors significantly associated with heart attacks.
* **CN**: 应用**卡方检验**（针对分类变量）与**皮尔逊相关性分析**（针对数值变量），科学筛选与心脏病发作具有显著相关性的特征。

### 3. Handling Data Imbalance | 攻克数据不平衡
* **EN**: Addressed the low prevalence of heart disease using advanced sampling techniques: **RandomOverSampler (ROS)**, **SMOTE**, and **RandomUnderSampler**. 
* **CN**: 针对心脏病样本较少的类别不平衡问题，采用了 **RandomOverSampler (ROS)**、**SMOTE** 及**欠采样**等多种技术平衡训练集。

---

## 🛠️ Tech Stack | 技术栈
- **Data**: Pandas, NumPy
- **Statistics**: Scipy, Statsmodels
- **Machine Learning**: Scikit-learn, Imbalanced-learn
- **Data Mining**: Mlxtend (Apriori)
- **Visualization**: Plotly, Matplotlib, Seaborn