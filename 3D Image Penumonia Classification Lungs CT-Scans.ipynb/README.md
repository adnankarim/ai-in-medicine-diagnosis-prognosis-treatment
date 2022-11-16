# 3D Image Penumonia Classification Lungs CT-Scans using CNN


## Data

- We used a subset of the [MosMedData: Chest CT Scans with COVID-19 Related Findings](https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1).
- This dataset consists of lung CT scans with COVID-19 related findings, as well as without such findings.
- We will be using the associated radiological findings of the CT scans as labels to build
a classifier to predict presence of viral pneumonia. Hence, the task is a binary classification problem.
- All the images are in the `nii.gz` format.

  <img src="./../images/2.png" alt="Result 1" style="height: 250px;width:500px;"/>

## Model
- The Model used in this project is [UNet](https://arxiv.org/abs/1505.04597).
-  The size of the input is 224 x 224 x 3, and the output is 224 x 224 x 1.
- The Pre-trained weights can be downloaded from [here](https://drive.google.com/drive/folders/1tM1LiTmOOMvsl6cCMf8HJmCpp1aL-p_l?usp=sharing).
- Optimizer: `Adam`
- Loss: `BCEWithLogits`

## Results

- ### Here are the prediction results obtained from the model.

    <img src="./R1.png" alt="Result 1" style="height: 150px;width:450px;"/>
    <img src="results/R2.png" alt="Result 2" style="height: 150px;width:450px;"/>
    <img src="results/R3.png" alt="Result 3" style="height: 150px;width:450px;"/>