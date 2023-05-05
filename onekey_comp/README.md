# Onekey组件

## 介绍
Onekey平台中拆分出来的组件，具体介绍的参考：http://www.medai.icu/thread/63 

* comp1-传统组学，传统组学pipeline，特征提取、筛选、建模、评估系列流程。
* comp2-结构化数据，csv、Excel格式数据，例如生理生化，临床数据、提取好特征的数据（深度特征）等建模。
* comp3-融合，包括前融合和后融合技术相关组件。
* comp4-What，深度学习特征提取，迁移学习；2D、3D数据都涵盖在此组件中。
* comp5-Which，ROI区域的自动勾画，涵盖2D、3D数据的识别逻辑。
* comp6-Sequence，序列化数据，构建中，当前为源码模式。
* comp7-Survival，生存分析，KM、Cox、Nomogram 相关组件。
* comp8-Modules，Onekey中的一些单独的模块用于做数据分析用的，例如ICC、指标分析之类的模块。

### Onekey视频

链接：https://pan.baidu.com/s/1x_FovKJYqcddtQSLTtuGFA?pwd=rb7b 
提取码：rb7b 
密码：www.medai.icu

#### 配置环境

将下载下来的OnekeyVideo，解压到任意位置，并且添加`ONEKEY_ROOT`到系统环境变量。对应的值为解压文件目录。  例如：

![img.png](http://www.medai.icu/storage/attachments/2022/03/26/060cGWTOEMWnnWyAQ1iMVnsTJyoQmSUfxyceSfFB.png)