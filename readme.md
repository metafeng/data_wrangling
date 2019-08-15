# Data Wrangling Summary

# 数据争论摘要

Wrangling是个奇怪的词。让我们检查一下定义。

- 作为不及物动词，指争吵，或愤怒而吵闹地争论。
- 作为及物动词，放马或放牧。

我们需要为好的结果争论我们的数据，否则可能会有后果。如果我们在争论之前分析、可视化或建模我们的数据，我们的后果可能是犯错误、错失冷静的洞察力和浪费时间。所以最佳实践就是争吵。

> **Data wrangling**, sometimes referred to as data munging, is the process of transforming and mapping data from one "raw" data form into another format with the intent of making it more appropriate and valuable for a variety of downstream purposes such as analytics. A data wrangler is a person who performs these transformation operations.    --**wikipedia**
>
> **数据争论**，有时也称为数据管理，是将数据从一种“原始”数据形式转换和映射到另一种格式的过程，目的是使其更适合于各种下游目的，如分析。数据管理员是执行这些转换操作的人。

这可能包括进一步管理、数据可视化、数据聚合、训练统计模型以及许多其他潜在用途。作为一个过程，数据争论通常遵循一组一般步骤，这些步骤从数据源提取原始形式的数据开始，使用算法(例如排序)对原始数据进行“管理”，或者将数据解析成预定义的数据结构，最后将结果内容存放到数据接收器中以供存储和将来使用。

# Jupyter Noteboks

了解收集，评估和清洗数据的数据争论过程。了解如何使用Python以编程方式处理数据并为更深入的分析做好准备。

- 模块01：  [数据争论简介](data_wrangling_template.ipynb)

通过简要的流程演练，确定数据争论过程的每个步骤（收集，评估，清理）。本模块数据集是Kaggle的在线职位发布数据集。

- 模块02： [收集数据](https://github.com/hufe09/DataWrangling/blob/master/Gather/Gathering.ipynb)

使用Python从各种来源和各种文件格式中收集数据。Rotten Tomatoes电影评分，影评和维基百科电影海报图片构成了本模块的数据集。

- 模块03： [评估数据](https://github.com/hufe09/DataWrangling/blob/master/Assess/Assessing.ipynb)

 使用Pandas以可视方式和编程方式评估数据质量和整洁问题。本模块数据集是一种名为Auralin的新口服胰岛素的模拟II期临床试验数据。

- 模块04：  [清洗数据](https://github.com/hufe09/DataWrangling/blob/master/Clean/Cleaning.ipynb)

 使用Pandas，清除您在“评估数据”模块中确定的质量和整洁问题。数据集是相同的：模拟新的口服胰岛素的第二阶段临床试验数据，称为Auralin。



> [个人博客](<https://hufe09.github.io/archive/?tag=Data+Wrangling>)