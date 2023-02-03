### 飞桨学习赛：PALM病理性近视预测

master只是默认分支，具体代码请看标签或发行版，已标注每份代码对应的分数

从 https://aistudio.baidu.com/aistudio/competition/detail/85/0/datasets 下载数据集并解压，还需要把`Classification.xlsx`转为`Classification.csv`

`main.ipynb`中需要修改的参数是
- `训练集图片所在文件夹`
- `写有训练集标签的csv路径`
- `测试集图片所在文件夹`