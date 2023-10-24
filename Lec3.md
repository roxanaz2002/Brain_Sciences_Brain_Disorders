# 
## 
### Brain Imaging Computing
- Structual (*T1w*)
  - Voxel Based Morphometry(VBM)(unit:voxel 体素)
    * tool: CAT, FSL 
    * tissue type: 灰质(G)，白质(W)，脑脊液(CSF); G+W+CSF=1
    * intensity -(probability)-> content -> density,volumn
    * 标准脑->segmentation(硬分割)->皮层reconstruction(重建)->geometric info-> 配准 
    * registration（对齐）设定标准大脑：标准空间，个体空间
  - Surface Based analysis(unit: vertex)
    - 3D-vertex,surface
    - tool: freesurfer
- functional(Bold)
  - resting state
    - amp 幅度，
    - 局部活动（）
    - 种族相关
  - activation(激活区检测) be actived: during task
    - GLM (广义线性模型)
- connectivity (Bold,dti)
  - SC: structual ~
  - CF: functional ~ (co-activity)
    - task 
    - resting
### Structure 脑图谱
  - 白色：头皮：brain extraction(剥头皮)
    - 配准
    - 连通域
  - 黑色：颅骨
#### 标准空间
* 模版：standard template 
* MNI：Montreal Neural Institute
### fMRI 
- 4D->3D
- 1995 Bharat Biswal
  - disease may impact the connection of these areas
  - noise clearing: find the correlation and anti-correlation in different brain area
- PNAS Fox et al,self reference
- 2004: brain a complex network/structure network
- NETWORK analysis
  - graph theory
  - disease -(balance broken)> network weakened/enhanced
  - focus -> 2006 function connection varies instantly/ construct connection hardly varies in moments
  - follow the current trend
  - mathematically easy to solve but does work on neuroscience(play the competition ON TIME! the prospect of the future matters look for new trend)
- FREEsurfer HCP Harvard 
- grab the demand of DOCTORS: they cannot programming...matlab
#### Rise a question
##### Cocktail party Problem
- signal processing ICA
- 三个话筒解混三种声音 decomposition
- samples
- 静息态fMRI功能连接研究ICA（until 2010）
##### ICA application
- resting state function network
- project: GUI design based on Windows(4D fMRI subject 1-100...)
- 
- 
