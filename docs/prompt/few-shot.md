# Few-shot

在模型训练过程中，如果每个类别只有少量样本（一个或者几个），研究人员希望机器学习模型在学习了一定类别的大量数据后，对于新的类别，只需要少量的样本就能快速学习，这就是 Few-shot Learning 要解决的问题。few-shot learning是meta-learning的一种，本质上是让机器学会自己学习（learn to learn），其实就是通过判断测试样本与训练样本的相似性，来推测测试样本属于什么类。

学习的目的是理解事物之间的不同，学会区分不同事物。给两张图像，不让学会是什么，而是学会是否相同。

One-shot Learning是Few-shot Learning的一种特殊情况