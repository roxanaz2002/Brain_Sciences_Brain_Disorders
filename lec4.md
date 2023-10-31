#
## 上节课回顾
### 配准 registration
#### VBM 分析
- 大脑形状不一样，如何配准？
  - 所有脑向标准脑配准，有缺陷
  - 自己和自己的大脑配准，路径最优，误差最小
  - *groupwise registration* 群组模版：两两配比较麻烦，群体配准
  - iteration：找到“大众脸”，产生average，和ave配准
  - 标准脑：模糊粗糙，平滑；单独
  - volume：粗配 -> 12参数仿射变换 affine； 精配：非线性deformation field 
- variability 变易
- 图论：module，网络information segregation/integration;connector hub;
- 流形
## 本节课学习内容
- 分子成像（PET,MRS）
- 灌注成像（ASL）
- 定量成像（qMRI,QSM）
### PET：癌症早筛 PET_CT/PET_MR
- 葡萄糖消耗越多黑色：大脑 膀胱 肝脏 心脏
- T1 T2 connectivity
- 功能成像
- 白质成像
- 分子成像：铁/葡萄糖
- 灌注成像：不同造影剂
- 放射性☢️价格昂贵(10,000/次)
- 
- 
### 大语言生成模型PET: 经济的早筛方法 
- fMRI-based Aβ phenotyping
- 大规模筛查：predict disease
- 低成本、高可行度
- 结构成像难以预测->PET是分子的 功能成像
- 
### 
#### T2-FLAIR
- 脑小血管病（中风的高危因素）磁共振显示高亮度：毛细血管堵塞，神经元坏死，游离水，高信号；老年痴呆产生的原因->
- 
#### T1c
- contrast enhance
- 对比剂注入->肿瘤增生细胞，需要快速增殖（血管内壁薄），血脑屏障被破坏->呈现高亮信号
- 频扫
- Ga 对比剂 肾功能不良者慎用
#### MRS 
- 不用造影剂
#### ASL
- 成像时间长
- 血液，H原子
- 信噪比
#### Quantitative MRI
- quantitative:髓鞘，铁，水
- 目前临床时间：1hour
- 科研前沿：多参数采集，基于AI的快速重建
