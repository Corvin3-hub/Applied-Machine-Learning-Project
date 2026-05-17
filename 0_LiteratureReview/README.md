# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: RA-UNet:A New Deep learning Segmentation Method for Semiconductor Wafer Defect Analysis on Fine-grained Scanning Electron Microscope (SEM) Images

  - https://www.researchgate.net/publication/370681497_RA-UNetA_New_Deep_learning_Segmentation_Method_for_Semiconductor_Wafer_Defect_Analysis_on_Fine-grained_Scanning_Electron_Microscope_SEM_Images
  - **Objective**:improve SEM defect quantitative analysis, overcome challenge of diverse defect morphologies, varying defect scales, and the intricate balance between defect areas and backgrounds
  - **Methods**:combined network structure = RA-UNet, 1. Focus on defects and reduce background info 2. UNet extracts morophological features
  - **Outcomes**:IoU score of 71.92 %
  - **Relation to the Project**: analysis of morphological features of individual defects, only few papers on this due to data limitation, interesting model architecture using transformer to extract defect first

- **Source 2**: Shinde et al. — Defect Detection in Photolithographic Patterns Using Synthetic Data

  - https://www.sciencedirect.com/science/article/pii/S240584402501761X
  - **Objective**: this paper studies deep learning for detecting photolithography defects in SEM images, especially when real labeled SEM data is limited
  - **Methods**: the authors generated synthetic SEM images with known bridge and break defects, automatically annotated them, and trained object detection models such as YOLOv8, SSD, and EfficientNet
  - **Outcomes**: YOLOv8 achieved the strongest result, with reported mean average precision of 96%, and when tested on real SEM data it detected 84.6% of bridge defects and 78.3% of break defects
  - **Relation to the Project**: introduces to different existing models, addresses issue of the limited data

- **Source 3**: [Title of Source 3]

  - **[Link]()**
  - **Objective**:
  - **Methods**:
  - **Outcomes**:
  - **Relation to the Project**:
