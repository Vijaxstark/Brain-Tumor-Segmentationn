# 🧠 Brain Tumor Segmentation using U-Net

📘 [View the Notebook](./Brain_Tumor_Segmentation_UNet.ipynb)  
🌐 [Open in nbviewer](https://nbviewer.org/github/Vijaxstark/Brain-Tumor-Segmentation/blob/main/Brain_Tumor_Segmentation_UNet.ipynb)

This project implements a U-Net based deep learning model for segmenting brain tumors in MRI scans. It was developed as part of a coursework project at IIITDM Kancheepuram.

![Notebook Preview](./489f1ce0-5645-4bb9-a184-f717b11cd09b.png)

## 📌 Objective
To segment brain tumors from MRI scans using deep learning techniques, specifically the U-Net architecture.

## 📁 Project Content

- 📓 Jupyter Notebook: `Brain_Tumor_Segmentation_UNet.ipynb`
- 📊 Dataset: LGG MRI scans from TCIA
- 📚 Techniques: U-Net architecture, Dice Loss, Custom Generators

## 🧰 Tools & Libraries

- Python
- TensorFlow / Keras
- NumPy, OpenCV, Matplotlib
- `ImageDataGenerator` for augmentation

## ⚙️ Key Features

- Preprocessing and loading of LGG dataset
- U-Net model for pixel-wise segmentation
- Dice loss to handle class imbalance
- Augmentation pipeline using `ImageDataGenerator`
- Visualization of segmentation outputs

## 📈 Sample Output
> "before and after" MRI + mask predictions from THE notebook.

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/Vijaxstark/brain-tumor-segmentation-unet.git
```

### Install Requirements
```bash
pip install -r requirements.txt
```

### Run the Notebook
Open `Brain_Tumor_Segmentation_UNet.ipynb` and run all cells.

## 📚 References
- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
- [The Cancer Imaging Archive (LGG Dataset)](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LGG)
