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
### 脑图谱
  - 白色：头皮：brain extraction(剥头皮)
    - 配准
    - 连通域
  - 黑色：颅骨
#### 标准空间
* 模版：standard template 
* MNI：Montreal Neural Institute
* 
