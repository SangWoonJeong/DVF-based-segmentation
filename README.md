# Segmentation using Deformable Vector Fileds based augmentation

## Introduction
Organ-at-risk segmentation is essential in adaptive radiotherapy (ART). Learning-based automatic segmentation can reduce committed labor and accelerate the ART process. In this study, an auto-segmentation model was developed by employing individual patient datasets and a deep-learning-based augmentation method for tailoring radiation therapy according to the changes in the target and organ of interest in patients with prostate cancer.


## Models 

The models used in our research are:
- **Augmentation: Voxelmorph**
- **Segmentation: U-net, nnU-net**


## Repository Structure

- **data/**: exmaple dataset
- **src/segmentation/**: segmentation model source, package 등
- **src/augmentation/**: augmentation model source, package 등
- **augmented data/**: augmented dataset
- **results/**: Stores the results and performance metrics of the models.
- **checkpoints/**: saved models.


## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/SangWoonJeong/DVF-based-segmentation.git
    ```
2. Navigate to the project directory:
    ```bash
    cd DVF-based-segmentation
    ```

## Results

The results section will include the performance metrics for each model under the specified delay times. This may include accuracy, precision, recall, and other relevant metrics.

## Publications

For more detailed information, refer to our published paper:
- **Deep-learning-based segmentation using individual patient data on prostate cancer radiation therapy**
- Authors: [Sangwoon JEong]
- Published in: [PLOS ONE]
- [https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0308181]


## Contact

For any questions or inquiries, please contact [sangwoonjeong93@gmail.com].
