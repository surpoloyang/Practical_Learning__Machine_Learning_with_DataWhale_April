# 波士顿房价预测数据集

### 数据集背景

- **来源**: Harrison, D. 和 Rubinfeld, D.L. 在1978年发表的论文《Hedonic prices and the demand for clean air》。
- **发表期刊**: Journal of Environmental Economics & Management, 第5卷，81-102页。

### 属性信息

输入特征（按顺序）:

1. **CRIM**: 城镇的人均犯罪率
2. **ZN**: 城镇住宅土地中超过25,000平方英尺地块的比例
3. **INDUS**: 城镇非零售商业英亩的比例
4. **CHAS**: 查尔斯河虚拟变量（如果区域毗邻河流则为1，否则为0）
5. **NOX**: 氧化氮浓度（每10亿分之几）[parts/10M]
6. **RM**: 每户住宅的平均房间数
7. **AGE**: 1940年以前建造的业主自住单位的比例
8. **DIS**: 到波士顿五个就业中心的加权距离
9. **RAD**: 可达性高速公路指数
10. **TAX**: 每10,000美元的全值房产税率[$/10k]
11. **PTRATIO**: 城镇的师生比例
12. **B**: 方程 B=1000(Bk - 0.63)^2 的结果，其中 Bk 是城镇黑人比例
13. **LSTAT**: 低收入阶层人口的百分比

输出变量:

1. **MEDV**: 业主自住房屋的中位价值，单位为千美元[k$]*（本次比赛中为**PRICE**）*

### 数据来源

- **StatLib** - 卡内基梅隆大学

### 相关论文

1. **Harrison, David & Rubinfeld, Daniel. (1978).** 论文链接: [Hedonic Housing Prices](https://www.sciencedirect.com/science/article/pii/009506967890066)
2. **Belsley, David A., Kuh, Edwin, & Welsch, Roy E. (1980).** 论文链接: [Regression Diagnostics](https://www.wiley.com/en-us/Regression+Diagnostics:+Identifying+Influential+Data+and+Sources+of+Collinearity-p-9780471055019)