

# 健康成人脑龄预测挑战赛

## 赛事背景
- **社会挑战**：中国进入人口老龄化社会，异常老化引起的疾病（如阿尔茨海默病、帕金森病）带来经济和社会问题。
- **研究意义**：通过大脑年龄预测来探索大脑老化过程中的异常变化，为研究大脑老化个体差异提供新视角。

## 赛事任务
- **目标**：基于脑结构图像预测大脑年龄。
- **数据提供**：数千例T1加权结构磁共振图像的全脑分割后脑区结构指标，如体积、表面积、厚度等。

## 评审规则
### 数据说明
- **数据来源**：全国15所大学医院，使用1.5 T MR设备采集了3000名正常成年志愿者的全脑结构磁共振图像。
- **数据应用**：该数据已用于中国人脑图Chinese2020的构建，以及不同脑结构的常模研究。
- **竞赛数据**：近2000例经过严格质控的健康成年人数据，包括性别、年龄、体积、表面积、厚度、平均曲率、高斯曲率以及MRI扫描仪类型。
- **数据集划分**：采用随机抽取方式，分为训练集和测试集。训练集提供所有信息，测试集不提供年龄信息。

#### 入组与排除标准
- **入组标准**：健康成人。
- **排除标准**：
  1. 各种神经精神疾病。
  2. 磁共振数据质量差。

### 评估指标
- **排名依据**：预测脑龄与实际生理年龄的平均绝对误差（MAE）。
- **MAE计算**：测试集的平均绝对误差，即多次测量的每次残差绝对值的平均值。
- **MAE公式**：

$$
MAE = \frac{\sum_{i=1}^{n} | \text pre_i - \text real_i |}{n}
$$

### 评测及排行
1. **数据下载**：比赛提供下载数据，选手在本地进行算法调试。
2. **结果提交**：在比赛页面提交结果。
3. **排名方式**：排行按照得分从低到高排序，排行榜将选择团队的历史最优成绩进行排名。

评审规则详细说明了数据的来源、如何划分训练集和测试集、入组与排除标准、评估指标的计算方法以及评测和排名的具体流程。这些规则为参赛者提供了清晰的评判标准和提交结果的指南。

## 作品提交要求
1. **文件格式**：CSV格式。
2. **文件大小**：无具体要求。
3. **提交次数**：每支队伍最多25次。
4. **文件说明**：UTF-8编码，第一行为表头。

## 赛程规则
- **赛制**：一轮赛制。
- **赛程周期**：6月30日至8月30日。
  - **开始**：6月30日10:00发布数据集，开启比赛榜单。
  - **截止**：8月30日17:00作品提交截止，8月31日10:00公布名次。

### 提交规范

- **截止时间**：09/02 23:59:59
- **联系方式**：若文件过大，可发送至官方邮箱AICompetition@iflytek.com
- **弃权规则**：未在截止时间内提交，官方会联系选手，若未接通或接通后3日内未提交，则视为弃权。

### 附加信息

- **提交规范文档**：可下载科大讯飞-代码审核规范以了解具体要求。

## 现场答辩
1. **邀请**：前三名团队参加科大讯飞全球1024开发者节并答辩。
2. **形式**：10分钟陈述+5分钟问答。
3. **评分**：作品成绩（70%）+现场答辩分数（30%）。

## 奖项设置
- **入围决赛**：
  - 科大讯飞1024开发者节全场通票
  - 决赛入围证书
  - 科大讯飞创孵基地绿色入驻通道
  - A.I.服务市场入驻特权
- **决赛胜出**：
  - 奖金：第一名5000元、第二名3000元、第三名2000元
  - 颁奖盛典：现场授予奖金、证书与定制奖杯
  - A.I.全链创业扶持
  - 绿色就业通道 & 实习就业Offer

