# MachineLearningBigHomework
 合肥工业大学宣城校区 计算机与信息系 计算机科学与技术22-4班 第1小组 机器学习大作业



①**说明：我们选取了kaggle平台上有关蘑菇是否可以食用的数据集，该数据集共有五万多条数据。数据集网址为：https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset/data**

<br>

②整个主分支中各个文件的介绍：

（1）mushroom_cleaned.csv是项目所用到的数据集

（2）MachineLearningBigHomework.ipynb是整个项目的notebook，包括了所有代码以及markdown解释说明

（3）MachineLearningBigHomework.html是生成的HTML，用于汇总给学委提交

（4）DroidSansFallback.ttf是一个字体文件，项目中部分代码依赖本字体让matplotlib能输出中文。同时，建议使用Windows环境运行本项目或在其他系统中安装微软黑体“SimHei”，项目同样依赖本字体解决部分中文输出问题。

（5）images文件夹是jupyter中插入的一些图片，删除或移动可能导致Jupyter中的图片无法正常显示。

（6）.ipynb_checkpoints是Jupyter编写过程中自动生成的自动保存和手动保存的快照。

<br>

③**jupyter notenook项目目录**

 - 环境设置<br>
 - 第一部分：数据集处理<br>
  1.1、读取数据集<br>
  1.2、对数据集进行分析<br>
    1.2.1 获取数据集的简单描述。<br>
    1.2.2 查看数据集的属性摘要<br>
    1.2.3 统计并对比可食用蘑菇和不可食用蘑菇数据量<br>
    1.2.4 对数据集中的其他八个特征量进行分析<br>
      1.2.4.1 使用直方图进行分析<br>
      1.2.4.2 绘制相关矩阵进行分析<br>
  1.3、基于分析对数据集进行处理<br>
    1.3.1 按照上面的数据分析，先删除所有菌盖直径大于1500的数据<br>
    1.3.2 再将菌柄高度在2.0附近的数据删除一部分<br>
    1.3.3 对处理完的数据进行检查<br>
  1.4、将数据集划分为训练集、测试集和验证集<br>
 - 第二部分：模型训练
  2.1、吴在彤<br>
    2.1.1 逻辑回归<br>
    2.1.2 支持向量机<br>
  2.2、张驰<br>
    2.2.1 梯度提升机<br>
    2.2.2 全连接神经网络<br>
    2.2.3 AdaBoost<br>
  2.3、苏昱铭<br>
    2.3.1 KNN<br>
    2.3.2 GBDT<br>
  2.4、胡浩鸿<br>
    2.4.1 LGBM<br>
    2.4.2 XGB<br>
    2.4.3 AdaBoost<br>
  2.5、祁子涵<br>
    2.5.1 极端随机树<br>
    2.5.2 决策树<br>
    2.5.3 随机森林<br>
  2.6、吴硕<br>
    2.6.1 朴素贝叶斯<br>
    2.6.2 AdaBoost<br>
 - 第三部分：分析与总结
  3.1、对所有模型的效果进行汇总并制作成表格<br>
  3.2、最佳模型评判<br>
  3.3、模型比较与讨论<br>
  3.4、错误分析<br>
  3.5、数据集局限性<br>
  3.6、模型泛化能力<br>
  3.7、改进方向<br>