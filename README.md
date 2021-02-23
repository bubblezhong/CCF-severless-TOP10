# CCF-severless-TOP10

比赛链接：https://www.datafountain.cn/competitions/468

比赛方案：

模型一：针对每个队列ID分别进行构建特征工程与训练lgb模型。

模型二：用全量数据训练一个lgb模型。

模型一和模型二按照4：6比例融合。

