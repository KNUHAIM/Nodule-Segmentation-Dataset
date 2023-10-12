# Nodule-Segmentation-Dataset

This README provides an overview of out nodule segmentation dataset.

## Dataset Description

- Dataset Name: [Nodule Segmentation Dataset]
- Data Type: Image Segmentation
- Data Format: Root image files and nodule segmentation masks
- Dataset Size: 1059 samples with 6000x4000 resolution
- Licencse: MIT License
- Provider: Department of Applied Biosciences, Kyungpook National University, Daegu 41566, Republic of Korea
- Dataset URL: https://drive.google.com/drive/folders/1ipgultABmQVe_LM8JMCuxXhJLKz4k9B6](https://docs.google.com/document/d/1kzpNrg8moTJowaXEh2YMQvEF1PyR8Zqh39jWP4uwCnQ/edit)
  
This dataset has been collected and prepared for nodule segmentation tasks.

Anyone can download our nodule segmentation dataset through above URL.

## Dataset Composition

The dataset consists of the following key components.

1. **Images:** The original image files in the dataset.
2. **Masks:** Segmentation masks for each image. Masks should be the same size as the original images.

Example dataset structure:

<pre>
```
.
├── Nodule_Segmentation_Dataset/
│   ├── images/
│   │   ├── 2018/
│   │   │   ├──  0.jpg
│   │   │   ├──  1.jpg
│   │   │   └──  ... 
│   │   ├── 2019/
│   │   │   ├──  0.jpg
│   │   │   ├──  1.jpg
│   │   │   └──  ...
│   ├── masks/
│   │   ├── 2018/
│   │   │   ├──  0.jpg
│   │   │   ├──  1.jpg
│   │   │   └──  ... 
│   │   ├── 2019/
│   │   │   ├──  0.jpg
│   │   │   ├──  1.jpg
│   │   │   └──  ...
```
</pre>
