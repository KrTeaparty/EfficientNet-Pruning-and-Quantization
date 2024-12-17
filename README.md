# EfficientNet-Pruning-and-Quantization
빅데이터기반분산-딥러닝혁신프로젝트의 기말과제로 EfficientNet에 대해 Pruning과 Quantization을 수행

### 실험 환경 구성
실험 환경
- python=3.10
- GPU: RTX 3080 10GB
- CUDA: 12.1

가상환경 생성
```
conda create -n assignment python=3.10
conda activate assignment
conda install pytorch==2.3.0 torchvision==0.18.0 -c pytorch -c nvidia
pip install torchprofile fvcore fast-pytorch-kmeans matplotlib
```
---
### 실행 파일
- Assignment_EfficientNet.ipynb 노트북의 셀을 순서대로 수행