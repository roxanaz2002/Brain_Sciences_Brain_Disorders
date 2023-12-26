# WEEK 4  
## Content
- 研究人类大脑结构的sMRI/及其基本分析技术
- 研究人类大脑功能的is-AMR/及其基本分析技术
- 研究人类大脑白质结构的MRI及其基本分析技术
- 分子成像 (PET、MRS)、灌注成像（ASL)、定量成像 (gMRl,QSM)
## Brain Imaging Computing
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
## Structure 脑图谱
  - 白色：头皮：brain extraction(剥头皮)
    - 配准
    - 连通域
  - 黑色：颅骨
### 标准空间
* 模版：standard template 
* MNI：Montreal Neural Institute
## fMRI 
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
### Rise a question
#### Cocktail party Problem
- signal processing ICA
- 三个话筒解混三种声音 decomposition
- samples
- 静息态fMRI功能连接研究ICA（until 2010）
#### ICA application
- resting state function network
- project: GUI design based on Windows(4D fMRI subject 1-100...)
### 婴儿脑图谱的分析(4-D data)
#### 分割 
- T1w T2W 
- correlation matrix
### Head motion distortion correction 头动校正
### EPI to Anat Image T1w,T2w
- result: well alighed images from different atlas
- Extensive preprocessing (denoising)
## Diffusion fRMI
### Free, Hindered and Restricted diffusion
- Major Cellular: 轴突-髓鞘-朗菲氏结
- 水分子 -(limited Brown motion)- H原子
- Anisotrophy: 判断水分子运动方式(球状：各向同性/椭球：六个变量) fiber tracking（fiber ）
- tractography（估计脑纤维）: 研究椭球长轴延伸方向(shade/color code: 蓝：上下，绿：前后，红色：左右)
- Brainconnectomics
#### Structure conncetivity: binary...
### Limitations of DTI
- tensor 六个自由度 张量分析，维度升高
- SMSI：弥散MRI 数据分析
- 分析流水线，质量控制

### Differences between T1, T2, T2Flair
1. **T1 (Longitudinal Relaxation Time):**
   - **Definition:** T1 is the time it takes for the longitudinal magnetization (Mz) to recover to 63% of its maximum value after it has been disturbed by a radiofrequency (RF) pulse.
   - **Indication:** T1-weighted images provide good contrast between different types of tissues. Tissues with short T1 times appear bright, while those with long T1 times appear dark.

2. **T2 (Transverse Relaxation Time):**
   - **Definition:** T2 is the time it takes for the transverse magnetization (Mxy) to decay to 37% of its maximum value after an RF pulse.
   - **Indication:** T2-weighted images are useful for highlighting differences in water content and detecting pathological changes in tissues. Fluid-filled structures and edema, for example, appear bright on T2-weighted images.

3. **T2* (Transverse Relaxation Time Star):**
   - **Definition:** T2* is similar to T2 but is more sensitive to magnetic field inhomogeneities caused by factors like susceptibility differences between tissues.
   - **Indication:** T2* is often used in functional MRI (fMRI) and susceptibility-weighted imaging (SWI) to enhance contrast and provide information about blood oxygenation levels. It is particularly useful for imaging veins and detecting areas of blood products.
