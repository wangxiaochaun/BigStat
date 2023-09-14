实验指导书

# 第一次实验

## 准备工作

### 环境配置

说明：本次实验及后续实验需要Python环境，以及Jupyter Notebook的支持。

* 检查自己的机器是否安装了Anaconda，如果没有请安装。下载及安装方式请参考官网[Anaconda](https://www.anaconda.com/download)。
* 使用Anaconda创建一个新的虚拟环境，命名为BigStat（这是本人的恶趣味，你也可以起任何你喜欢的名称），python版本最好选择3.7。过于新的版本可能会导致后续代码的bug（当然所有bug都是可以解决的）。但不要选择2.x版本，它们已经落后于时代了。Anaconda创建虚拟环境请参考[CSDN](https://blog.csdn.net/zouxun660/article/details/126121013)，这里给出一个参考：

```bash
conda create -n BigStat python=3.7
```

* 激活虚拟环境，安装本次实验需要的一些包，主要有`numpy, pandas, matplotlib`，以及后续可能会用到的一些包，如`sklearn(scikit-learn), torch(pytorch)`等。你也可以在任何时候安装后续的包。如果你已经决定安装`pytorch`，请确认安装的是CPU还是GPU版本。推荐使用GPU版本，但前提是你的机器得有独立显卡。这里给出一个参考：

* 继续安装`jupyer(notebook)`，这是运行jupyter notebook(.ipynb)的包。

```bash
pip install numpy, pandas, matplotlib, notebook
```

### 使用Jupyter Notebook

在命令行中运行

```python
jupyter notebook
```

即可使用Jupyter Notebook。

有关Jupyter notebook的使用方法很多，这里随便挑了一个(不一定好使)[Jupyter Notebook简洁教程](https://blog.csdn.net/u013023297/article/details/71082881)

### 关于Markdown

Jupyter notebook中包含两种cell，一种是代码单元，这里不做赘述；另一种是markdown单元，遵循markdown语法。有关markdown的教程也有很多，这里随便挑了一个（不一定靠谱）[Markdown使用指北](https://www.cnblogs.com/WHU-TD/p/13830591.html)

## 正式工作

### 资料来源

实验指导书和相应的资源均已上传至Github：[戳这里](https://github.com/wangxiaochaun/BigStat)

### 代码部分

* 阅读HW1.zip中的PartA和PartB，这两部分展示了使用Python的Pandas和Matplotlib如何分析数据。相应的北京市空气质量数据也在压缩包中，运行代码时请确保文件读取的路径是正确的。
* 阅读PartC，这部分代码需要自己完成，相应的数据文献是ReportCard1和ReportCard2。同样请注意文件路径。

### 作业提交

* PartC执行完毕后，会有相应的输出。请将PartC.ipynb导出为pdf文件，上传到下述位置：

==[作业提交地址](https://send2me.cn/mfGsnX0q/R4aRuX8E8fGl9Q)==

**注意：作业截止时间为9月30日。**