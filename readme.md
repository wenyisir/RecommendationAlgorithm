# 推荐系统中的多目标算法

![Python](https://img.shields.io/badge/Python-3.9.5-green?logo=python)![TensorFlow Versions](https://img.shields.io/badge/TensorFlow-2.8.0-blue.svg)

### 简介

- 实现推荐系统中的多目标算法，并使用公开数据集评测
- 使用[微信视频号推荐算法比赛](https://algo.weixin.qq.com/problem-description)数据集

- 为了贴合工业界使用情况，使用`TensorFlow Estimator`框架，数据format为`Tfrecord`；



### 多任务Models列表

| Model |                            Paper                             | Best_read_commet_AUC | Best_like_AUC | Best_click_avatar_AUC |
| :---: | :----------------------------------------------------------: | :------------------: | :-----------: | :-------------------: |
| ESMM  | [2018] [Entire Space Multi-Task Model: An Effective Approach for Estimating Post-Click Conversion Rate](https://arxiv.org/abs/1804.07931) |                      |               |                       |
| MMOE  | [2018] [Modeling Task Relationships in Multi-task Learning with Multi-gate Mixture-of-Experts](https://dl.acm.org/doi/abs/10.1145/3219819.3220007) |                      |               |                       |
|  PLE  | [2020] [Progressive Layered Extraction (PLE): A Novel Multi-Task Learning (MTL) Model for Personalized Recommendations](https://dl.acm.org/doi/10.1145/3383313.3412236) |                      |               |                       |