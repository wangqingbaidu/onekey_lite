# onekey_lite

Onekey平台试用版。官网：www.medai.icu

## 安装环境

```buildoutcfg
conda install cudatoolkit==11.3.1 -c conda-forge -y
conda install cudnn==8.2.1 -c conda-forge -y
pip install torch==1.8.1+cu111 torchvision==0.9.1+cu111 torchaudio==0.8.1 -f https://download.pytorch.org/whl/torch_stable.html -I
pip install -r requirements.txt
```

## Onekey组件

## 介绍

Onekey平台中拆分出来的组件，具体介绍的参考：http://www.medai.icu/thread/63 

* comp0-MIET，Onekey独有的数据预处理模块。
* comp1-传统组学，传统组学pipeline，特征提取、筛选、建模、评估系列流程。
* comp2-结构化数据，csv、Excel格式数据，例如生理生化，临床数据、提取好特征的数据（深度特征）等建模。
* comp4-What，深度学习特征提取，迁移学习；2D、3D数据都涵盖在此组件中。
* comp7-Survival，生存分析，KM、Cox、Nomogram 相关组件。
* comp8-Modules，Onekey中的一些单独的模块用于做数据分析用的，例如ICC、指标分析之类的模块。
* Comp9-Solutions, Onekey平台的解决方案。