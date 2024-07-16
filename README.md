One of the most popular machine learning models for classifying images is neural networks. But because neural networks are so dependent on the input data, even a small change in the input can have a significant impact on the output. In this master thes is, we present a novel approach for image preprocessing and classification optimization using genetic algorithms in conjunction with HSV color thresholding, channel shifting, and image masking techniques. Our goal is to build a highly efficient model with optimal architecture and classification accuracy. We tested our approach on 12 diverse datasets collected from Kaggle archives, which vary in data types and classification complexities.Our experimental results demonstrated that the proposed approach achieved more efficient results on 10 out of the 12 datasets compared to traditional methods. This highlights the effectiveness of our genetic algorithm-based optimization in improving image classification accuracy across various types of data.

## Experemental:
In this work we have used 12 datasets collected from Kaggle archives, for the experimental part of our work, in order to increase the variety of the data types, and the classification complexity.
Kaggle however is a multipurpose web platform, a subsidiary of Google LLC, is an online community of data scientists and machine learning practitioners. Kaggle allows users to find and publish data sets, explore and build models in a web-based data-science environment, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges. [14]
the table below summarizes the characteristics of the chosen data sets:

#### Dataset Descriptions

| Index | Dataset                   | Number of Classes | Number of Instances |
|:-----:|---------------------------|-------------------|---------------------|
|   1   | Bean Leaf Lesions         | 3                 | 1167                |
|   2   | Chicken disease           | 4                 | 6508                |
|   3   | Covid19                   | 3                 | 272                 |
|   4   | Dog or cat                | 2                 | 697                 |
|   5   | dog-breeds                | 8                 | 541                 |
|   6   | flowers                   | 5                 | 4317                |
|   7   | hand-sign                 | 10                | 1431                |
|   8   | Lemon                     | 2                 | 2076                |
|   9   | Lung X-Ray Image          | 3                 | 3475                |
|  10   | Monkeypox Skin Lesion     | 2                 | 228                 |
|  11   | R-P-S                     | 3                 | 2188                |
|  12   | SkinCancer                | 2                 | 3297                |


### Some data sets before and after

| Index | Dataset                   | Original Data | Gaussian Blur | Median Blur | Laplacian Filter | Unsharp Mask | Bilateral Filter | HOG  | LBP  | Approach |
|:-----:|---------------------------|--------------:|--------------:|------------:|-----------------:|-------------:|-----------------:|------:|------:|---------:|
|   1   | Bean Leaf Lesions         |         33.9  |          39.9  |       42.29  |            31.64  |        36.48 |            40.42  | 37.61 | 34.12 |     49.6 |
|   2   | Chicken disease           |         48.73 |          53.44 |       47.46  |            43.32  |        53.69 |            51.82  | 47.01 | 53.41 |     72.7 |
|   3   | Covid19                   |         43.61 |          46.25 |       47.5   |            45.27  |        44.02 |            35.27  | 36.66 | 40    |     78.05 |
|   4   | Dog or cat                |         49.04 |          47.14 |       50.95  |            51.42  |        49.52 |            45.23  | 48.57 | 50.95 |     55.71 |
|   5   | dog-breeds                |         12.75 |          17.68 |       12.9   |            18.45  |        17.24 |            16.61  | 15.9  | 10.2  |     43.12 |
|   6   | flowers                   |         34.64 |          39.82 |       43.68  |            35.65  |        41.12 |            41.14  | 34.41 | 26.9  |     34.01 |
|   7   | hand-sign                 |         11.39 |          14.65 |       12.79  |            74.18  |        16.04 |            14.41  | 79.3  | 15.58 |     92.79 |
|   8   | Lemon                     |         62.92 |          62.47 |       61.79  |            77.02  |        59.17 |            57.61  | 82.69 | 50.72 |     89.56 |
|   9   | Lung X-Ray Image          |         46.69 |          56.76 |       54.2   |            73.23  |        55.99 |            50.74  | 73.61 | 41.97 |     76.68 |
|  10   | Monkeypox Skin Lesion     |         60.95 |          53.57 |       56.42  |            53.75  |        56.42 |            57.85  | 45    | 52.14 |     53.81 |
|  11   | R-P-S                     |         38.47 |          40.65 |       43.37  |            48.84  |        37.28 |            36.51  | 76.25 | 39.42 |     76.41 |
|  12   | SkinCancer                |         63.23 |          60.7  |       59.09  |            62.12  |        53.13 |            57.27  | 62.22 | 52.52 |     74.04 |

### Dataset Processing Approaches Comparison

![image](https://github.com/user-attachments/assets/a6c7409c-5a29-40cf-91c5-98a48d6331db)




## 💻 Languages and Tools:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Opencv](https://img.shields.io/badge/Opencv-FF4A00?style=for-the-badge&logo=Opencv&logoColor=white)
![sklearn](https://img.shields.io/badge/SkLearn-HA4A00?style=for-the-badge&logo=Sklearn&logoColor=white)
