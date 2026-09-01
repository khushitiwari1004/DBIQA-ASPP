# DBIQA-ASPP

Official implementation of **DBIQA-ASPP: Dual-Branch Image Quality Assessment with Atrous Spatial Pyramid Pooling (ASPP).**

## Overview

DBIQA-ASPP enhances the Dual-Branch Image Quality Assessment (DBIQA) framework by integrating an Atrous Spatial Pyramid Pooling (ASPP) module into the deepest feature extraction stage to capture multi-scale contextual information.

## Repository Contents

- train.ipynb – Training notebook
- test.ipynb – Qualitative inference notebook
- DBIQA_VGG_ASPP.py
- DBIQA_ResNet_ASPP.py
- DBIQA_Squeeze_ASPP.py
- DBIQA_mobileV2_ASPP.py
- DBIQA_EfficientNet_ASPP.py

## Requirements

- Python 3.10
- PyTorch
- torchvision
- NumPy
- Pandas
- SciPy

## Usage

1. Open `train.ipynb` or `test.ipynb` in Google Colab or Jupyter Notebook.
2. The notebooks automatically clone the original DBIQA repository.
3. Place the ASPP backbone files in the cloned repository as instructed in the notebook.
4. Run all cells.

## Citation

If you use this code in your research, please cite our paper.
