This study develops a breast cancer segmentation model on ultrasound images using the Residual U-Net architecture enhanced with ASPP, along with scSE and SCAB attention modules to improve performance on low-contrast, noise-prone images. The dataset used is Breast Ultrasound Images Dataset(BUSI). Various loss functions—including Binary Cross-Entropy, Dice Loss, Tversky Loss, Focal Tversky Loss, and Lovász Hinge Loss—are applied to optimize segmentation. Model performance is evaluated using IoU, Dice Similarity Coefficient, Recall, Precision, and Hausdorff Distance.


# **DATASET**
- This project using Breast Ultrasound Images Dataset(BUSI) 2018. 
- The data collected at baseline include breast ultrasound images among women between 25 and 75 years old. This data was organized in 2018. The number of patients is 600 females, patients. The dataset consists of 780 images with an average image size of 500*500 pixels. The images are in PNG format. The ground truth images are presented with original images. The images are categorized into three classes, which are standard, benign, and malignant.
- Link for dataset: https://www.kaggle.com/datasets/sabahesaraki/breast-ultrasound-images-dataset/data?select=Dataset_BUSI_with_GT 


# **PREPROCESSING DATA**


# **MODEL**
