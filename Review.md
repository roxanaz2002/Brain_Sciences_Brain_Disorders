# final review
## MRI
### CT v MRI - brain
- CT is a map of tissue density – white areas represent higher density tissues than blacker areas
- MRI is a map of proton energy in tissues of the body – white areas represent high ‘signal’
- Cerebrospinal fluid (CSF) is low density on CT
- On T2 MRI image the CSF is white – indicating high signal
- White areas on an X-ray or CT image = high density
- White areas on an MRI image = high signal
### sMRI & fMRI & dMRI
#### sMRI
1. **Voxel-Based Morphometry (VBM):**
   - **简介：** VBM是一种分析整个脑体积和局部脑结构的技术。它通过对脑图像进行统计学分析，比较不同个体或组之间的灰质体积差异。
   - **基本步骤：** 
      - 图像获取和预处理
      - 图像分割，将脑分为灰质、白质、和脑脊液
      - 归一化处理，以便进行组间比较

2. **Surface-Based Analysis:**
   - **简介：** 表面分析侧重于分析大脑的皮层表面，更注重形态学变化。它可以用于研究局部解剖学的差异，例如褶皱和沟回的形状。
   - **基本步骤：**
      - 三维大脑重建
      - 表面参数提取
      - 表面统计分析

3. **Software and Toolkits:**
   - **常用软件：** FreeSurfer、SPM (Statistical Parametric Mapping)、FSL (FMRIB Software Library) 等。
   - **基本用途：** 这些工具包提供了用于脑结构分析的图像处理和统计学工具，简化了研究人员的工作流程。

4. **Major Processing Steps:**
   - **预处理：** 包括图像校正、配准、空间归一化等。
   - **分割：** 将脑组织分为灰质、白质、脑脊液等。
   - **特征提取：** 提取关键的形态学和结构特征。
   - **统计分析：** 使用统计模型比较不同组群之间的结构差异。

#### rs-fMRI及其基本分析技术
1. **Activity:**
   - **简介：** 通过监测大脑区域的血流和氧合水平变化，揭示不同任务或刺激条件下的大脑活动。
   - **基本步骤：**
      - 数据采集：获得大脑在特定任务或条件下的功能磁共振成像数据。
      - 预处理：包括去噪声、运动校正等。
      - 活动分析：通过建模大脑区域的信号变化来识别激活区域。

2. **Co-activity:**
   - **简介：** 研究大脑不同区域之间的协同活动，揭示它们如何一起工作以执行特定的功能。
   - **基本步骤：**
      - 功能连接分析：通过相关性或其他统计方法来探测不同区域之间的同步性。

3. **Resting-State Brain Networks:**
   - **简介：** 在安静状态下（不执行特定任务）研究大脑区域之间的同步活动，形成“静息态”网络。
   - **基本步骤：**
      - 网络提取：通过独立成分分析（ICA）等方法提取不同的网络。

#### 研究人类大脑白质结构的dMRI及其基本分析技术

1. **Diffusion Magnetic Resonance Imaging (dMRI):**
   - **简介：** dMRI测量水分子在生物组织中的扩散，对白质纤维束进行成像。
   - **基本步骤：**
      - 获取扩散加权成像数据
      - 重建扩散张量或其他模型
      - 分析白质纤维束的定向和完整性

2. **Analysis Techniques:**
   - **Tractography：** 通过在图像中追踪水分子扩散方向，可视化和分析白质纤维束的结构。
   - **Fractional Anisotropy (FA)：** 衡量水分子在组织中扩散方向的一致性，提供关于白质结构的信息。


### Tissue differentiation - Fat v water
- Protons in the body realign and dephase with varying rapidity depending on the tissue type
- Detecting the signal after different time intervals allows different tissue types to be highlighted
- Protons in fat realign quickly with high energy and produce high T1 signal, producing 'T1-weighted' images (highlight fat) 
- Protons in water dephase slowly, exploited to produce 'T2-weighted' images (highlight water)
## MRI interpretation
### Contrast agents(对比剂)
- Gadolinium: the most common MRI contrast agent (can be given intravenously or injected directly into a body part)
- Abnormal tissue may enhance more than surrounding normal tissue following intravenous gadolinium; may also retain gadolinium longer than normal tissue
### Planes
- axial 轴位 
- coronal 冠状位
- sagittal 矢状位
- oblique 斜位
### Sequences: T1,T2,T2 Flair
These times are related to the behavior of hydrogen nuclei (protons) in a magnetic field, visualizing anatomy and pathology
- T1: weighted image: fat appears bright and fluid appears dark.
- T2: weighted image: visualizing fluid-filled structures and pathology. Fluid appears bright and fat appears dark.
Look at the fat-sensitive T1 images which often provide good anatomical detail of the area being studied
Compare with the water-sensitive images – such as the T2-weighted or STIR images
 - **Remember**
    - On T1 – 1 tissue type is bright – FAT
    - On T2 – 2 tissue types are bright – FAT and WATER
