# Task 1 – Installation

## 1. Anaconda3
Download: https://www.anaconda.com/products/distribution
```bash
bash Anaconda3-<version>-Linux-x86_64.sh
```

## 2. PyTorch
```bash
pip install torch torchvision torchaudio
```
Docs: https://pytorch.org/get-started/locally/

## 3. TensorFlow 2.0
```bash
pip install tensorflow
```

## 4. VSCode
```bash
sudo snap install code --classic
```
Download: https://code.visualstudio.com/

## 5. PyCharm
```bash
sudo snap install pycharm-community --classic
```
Download: https://www.jetbrains.com/pycharm/

## Verify
```python
import torch; print(torch.__version__)
import tensorflow as tf; print(tf.__version__)
```
