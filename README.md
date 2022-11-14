# CT_lung_3D_segmentation

In order to detect lung lesions in CT 3D volumes, the lung needs to be segmented from the images. This project inspired by the Kaggle Data Science Bowl 2017, aimed to automate 3D lung segmentation from the CT scans using a 3D U-Net model. These allow calculation of paramterers such as the lung volume and Percentile Density (PD) from the CT scans. The dataset provides 2D and 3D images along with the masks provided by radiologists. The code was written for use in Google Colab and the dataset can be directly downloaded from the Kaggle database with personal API tokens.


### Mask predictions from a CT series volume
![alt text](https://raw.githubusercontent.com/rekalantar/CT_lung_3D_segmentation/master/results/subsample_pred.png)



### Prediction of lung volume from the volumetric CT scans
![alt text](https://raw.githubusercontent.com/rekalantar/CT_lung_3D_segmentation/master/results/full_scan_prediction.png)
