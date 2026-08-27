# Flower Product dataset
This repository provides the dataset used in our research paper. It includes all necessary files to reproduce the experiments and analyses described in the manuscript.
This repository provides the dataset used in our research. The copyright of all product images in this dataset belongs to Hana Cupid Co., Ltd. and is used with permission.
https://www.i879.com/

## General purpose:

This repository contains the dataset used in our research paper titled "Impression evaluation of product images using deep neural network".

## With paper citation:

Dataset accompanying our paper "Impression evaluation of product images using deep neural network" presented at Neural Computing and Applications, 2025.

```text
@article{yamagiwa2025impression,
  title={Impression evaluation of product images using deep neural network},
  author={Yamagiwa, Ayako and Goto, Masayuki},
  journal={Neural Computing and Applications},
  volume={37},
  number={16},
  pages={10215--10242},
  year={2025},
  publisher={Springer}
}
```

## Data Structure

```text
flower_product/
├── annotation_result/
│   ├── index001_eval_axis_cute.csv
│   ├── index002_eval_axis_cute.csv
│   └── ...
└── README.md
```

### Image Files

The image files are not stored directly in this GitHub repository because of their large file size.
Please download the image files from the following Google Drive folder:
https://drive.google.com/drive/folders/1wxzWCPhJdaYl3THhlozLSS8O6YbSq6TM?usp=sharing

After downloading, place the image files as follows:
```text
flower_product/
└── target/
    ├── 0001.jpeg
    ├── 0002.jpeg
    ├── 0003.jpeg
    └── ...
```

### Annotation Files

The annotation results are stored in:
flower_product/annotation_result/
Each annotation file is named as follows:
indexXXX_eval_axis_cute.csv
The cute part indicates the evaluation axis.
