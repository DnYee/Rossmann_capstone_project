# Rossmann_capstone_project
Udacity capstone project
(from Kaggle Competition)

## **题目描述**


Rossmann是欧洲的一家连锁药店。 在这个源自Kaggle比赛[Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales/data)中，我们需要根据Rossmann药妆店的信息（比如促销，竞争对手，节假日）以及在过去的销售情况，来预测Rossmann未来的销售额。

## 数据下载
此数据集可以从Kaggle上[下载](https://www.kaggle.com/c/4594/download-all)。

## 环境
该项目使用到matplotlib、seaborn、xgboost、sklearn、numpy、pandas

## 文件说明
forcasts_md.csv 是XGB模型预测结果乘上0.995后的结果，forcasts_md_wh0995.csv 是XGB模型预测结果，forcasts_dtr.csv是DecisionTreeRegression预测结果。

**（除去网格搜索部分代码，代码运行时间约为60分钟，网格搜索时间未知）** 

