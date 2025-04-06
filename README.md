# 深度学习第一次代码课

_本次课程将介绍最基本的深度学习的工具pytorch的安装与使用，并完成一些基本的模型的构建与训练_

__日期:__ 2025年4月8日

__主讲人:__ 刘翀鸣

-----

- 推荐通过Anaconda安装python，官方网站：<https://www.anaconda.com/download/success>。

- 推荐使用Visual Studio Code（VS Code）进行代码的编辑与运行，官方网站：<https://code.visualstudio.com/>。

-----

## 安装pytorch与相关常用的宏包

```bash
# new python environment for pytorch
conda create -n torch python=3.10
# activate the new environment
conda activate torch
# install basic packages
conda install -y numpy matplotlib seaborn tqdm scikit-learn jupyter ipython pandas
# install pytorch
conda install pytorch torchvision torchaudio -c pytorch -c nvidia -y
```
最后一行具体的安装pytorch的命令可以参考官网： <https://pytorch.org/get-started/locally/>。
