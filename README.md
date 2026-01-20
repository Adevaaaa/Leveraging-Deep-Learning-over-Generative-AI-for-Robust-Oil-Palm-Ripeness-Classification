# Leveraging Deep Learning over Generative AI for Robust Oil Palm Ripeness Classification

This repository contains the dataset and source code.

## Dataset Description

The dataset used in this research is a combination of secondary data and primary data collected to enhance model performance.

### Data Sources
* **Omar et al. (2024):** Provided the base dataset of 439 images.
* **Primary Data:** Additional images collected by the author.

### Class Distribution
The images are categorized into three ripeness levels:

| Category | Omar et al. (2024) | Combined Total | Description |
| :--- | :---: | :---: | :--- |
| **Underripe** | 164 images | 64 images | Not yet ready for harvest |
| **Ripe** | 201 images | 153 images | Optimum stage for oil production |
| **Overripe** | 74 images | 34 images | Past the optimum harvest window |
| **Total** | **439** | **690** | |

## Project Structure
```
├── Data Research/
│   ├── Unripe/       
│   ├── Ripe/            
│   └── Overripe/        
├── Palm Oil Ripeness Transfer Learning (1).ipynb           
└── README.md
```

### Citation
Omar, Z., Majeed, A. P. P. A., Rosbi, M., Ghazalli, S. A., & Selamat, H. (2024). Outdoor oil palm fruit ripeness dataset. Data in Brief, 55, 110667.
