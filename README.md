# paper
8.9
  看差分隐私，寻找一个动态规划的解决策略来实现GAN网络所生成的表征达到可用性和隐私性之间的平衡。
8.17
跑faster rcnn模型：使用预训练resnet101时，模型太大，耗光了一块GPU的8G内存，无法运行。 更换resnet34尝试训练。
resnet34可以跑，但是类别标签不对，并且预测结果很差，验证集出现tensor为负，无法运行的情况。
8.18
eval仍处于失败：尝试更换paddle detection 2.2仍然失败，调大s-epoch仍然不行，现在怀疑是数据标注问题。
