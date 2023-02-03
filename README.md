# 飞桨学习赛：PALM病理性近视预测

### 项目说明

基于[飞桨学习赛：PALM病理性近视预测](https://aistudio.baidu.com/aistudio/competition/detail/85/0/introduction)，验证学习众多的图像分类模型

1. 首先主要跟随[飞桨教程](https://www.paddlepaddle.org.cn/tutorials/projectdetail/4464926)验证了VGG、GoogLeNet、AlexNet和ResNet模型，三个模型在训练集上都能达到95%左右的准确率，但在测试集上只有50-55%的准确率，主要是没有合理划分训练集和验证集，以及没有对模型正则化处理。接下来的优化方向是数据增广、空洞卷积，尽可能充分利用好训练集高分辨率的优势

### 快速开始

1. 从发行版中选择合适的代码并克隆到本地

1. 从 https://aistudio.baidu.com/aistudio/competition/detail/85/0/datasets 下载数据集并解压

1. 把`Train`目录下的`Classification.xlsx`转为`Classification.csv`

1. 修改`main.ipynb`中的参数并运行
    - `训练集图片所在文件夹`
    - `写有训练集标签的csv路径`
    - `测试集图片所在文件夹`
