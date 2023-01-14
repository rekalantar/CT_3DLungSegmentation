# 3D Patch-Based Lung Segmentation on CT

Lung CT segmentation is an important task in the field of medical imaging, as it allows for more accurate diagnosis and treatment planning for lung diseases such as lung cancer, chronic obstructive pulmonary disease (COPD), and pneumonia.

Accurate segmentation of the lungs in a CT scan can help radiologists identify and measure the size and location of tumors or other abnormalities within the lungs. It can also be used to automatically extract quantitative information such as lung volumes and airway measurements, which can be used to aid in the diagnosis and treatment of lung diseases.

Furthermore, in the field of machine learning, lung CT segmentation is used as a pre-processing step for many medical image analysis tasks, such as nodule detection, classification, and registration.

In this tutorial, we will design an end-to-end AI framework in PyTorch for 3D segmentation of the lungs from CT. [Read Full Article](https://medium.com/@rekalantar/unlocking-the-potential-of-ai-in-medical-imaging-3d-lung-ct-segmentation-in-pytorch-d7ca1b17ae98)

<p align="center">
  <img alt="Lung CT Segmentation" src="https://github.com/rekalantar/CT_3DLungSegmentation/blob/master/assets/lung_neon_box.png?raw=true" width="30%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Lung CT Segmentation" src="https://github.com/rekalantar/CT_3DLungSegmentation/blob/master/assets/human_lung_overlay?raw=true" width="30%">
&nbsp; &nbsp; &nbsp; &nbsp;
<img alt="Lung CT Segmentation" src="https://github.com/rekalantar/CT_3DLungSegmentation/blob/master/assets/lung_neon.png?raw=true" width="30%">
&nbsp; &nbsp; &nbsp; &nbsp;
</p>

## Result ## 
The curves of training loss and validation Dice score after training for 500 epochs
![3D Lung CT training](https://github.com/rekalantar/CT_3DLungSegmentation/blob/master/results/train_val_curves.png)

Segmentation result on a test patient
![3D Lung CT Results](https://github.com/rekalantar/CT_3DLungSegmentation/blob/master/results/seg_results.png)
