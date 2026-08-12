# Lung Tumor Segmentation using Neural Networks

## Overview
This project implements a deep learning solution for lung tumor segmentation in medical images. The work demonstrates the application of neural networks to medical image analysis, specifically using the U-Net architecture for precise tumor boundary detection and segmentation.

## Project Description
This is a mini-project developed as part of a Neural Network course module, focusing on:
- **Medical Image Analysis**: Processing and analyzing CT/medical imaging data
- **Segmentation Task**: Automatically identifying and delineating lung tumor regions
- **Deep Learning Implementation**: Using convolutional neural networks (CNN) for automated segmentation

## Architecture
The project utilizes the **U-Net architecture**, a popular encoder-decoder network specifically designed for medical image segmentation tasks. The U-Net architecture is particularly effective for:
- Limited training data scenarios
- Precise localization of tumor regions
- Preserving fine anatomical details

## Repository Structure
```
├── notebooks/              # Jupyter notebooks containing experiments and analysis
├── src/                    # Python source code for models and utilities
├── README.md              # This file
└── Architecture diagrams  # Visual representations of the U-Net model
```

## Contents
- **Jupyter Notebooks** (93.4%): Exploratory data analysis, model training, and result visualization
- **Python Code** (6.6%): Reusable utility functions and model implementations

## Requirements
- Python 3.7+
- TensorFlow/Keras or PyTorch
- NumPy, Pandas
- Scikit-image (for image processing)
- Matplotlib (for visualization)

## Key Features
- Deep learning-based segmentation model
- U-Net encoder-decoder architecture
- Training and evaluation pipelines
- Result visualization and analysis
- Documentation with architecture diagrams

## Usage
1. Review the Jupyter notebooks in the `notebooks/` directory for the complete workflow
2. The notebooks document data loading, preprocessing, model training, and evaluation
3. Python modules in `src/` contain reusable utility functions

## Results
The model demonstrates effective segmentation of lung tumors, with comprehensive performance evaluation documented in the notebooks.

## Author
Dev Himakara

## License
This project is provided as-is for educational and research purposes.

## Citation
If you use this work in your research, please cite as:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21896502.svg)](https://doi.org/10.5281/zenodo.21896502)

## Contact
For questions or inquiries about this project, please reach out via GitHub.
