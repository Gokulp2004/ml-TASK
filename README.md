# ml-TASK

CIFAR-10 sparse CNN pruning notebook with a train-and-evaluate workflow.

## Files
- cifar10_sparse_cnn_pruning.ipynb

## Overview
The notebook trains a prunable CNN on CIFAR-10, tracks sparsity during training, and saves the best model checkpoint.

## Requirements
- Python 3.10+
- torch
- torchvision

## Usage
1. Open the notebook in Jupyter or VS Code.
2. Make sure PyTorch and torchvision are installed.
3. Run the notebook cells top to bottom.
4. The best checkpoint is saved as best_pruned_model.pth.

## Notes
- Dataset downloads into the ./data folder.
- Training may take time depending on whether CUDA is available.
