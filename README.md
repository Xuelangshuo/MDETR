# MDETR
## 实验原理
基于DETR的小样本目标检测，基于最新的算法进行改进
本次实验基于改进后的DETR模型，在公开小样本目标检测数据集MS COCO上进行了训练和测试，结果显示训练的模型能够消除novel类候选框不准所带来的限制并且能够有效利用类间相关性，减少误分类，增强相似或相关类之间的泛化。
## 实验效果
![image](https://github.com/Xuelangshuo/MDETR/assets/88080333/5587890c-0a2c-41ed-98d9-ce0cdf390ca6)
## 安装
### 实验环境
你必须具有NVIDIA GPU才能运行代码。

使用以下环境设置开发和测试实现代码:
- Ubuntu LTS 20.04
- NVIDIA RTX 3090 (32GB)
- CUDA 11.4
- Python == 3.7
- PyTorch == 1.12
- GCC == 7.5.0
- cython, pycocotools, tqdm, scipy
我建议使用上面的准确设置。如果是其他环境，应满足以下条件：Linux, Python>=3.7, CUDA>=9.2, GCC>=5.4, PyTorch>=1.5.1, TorchVision>=0.6.1。
### 实验代码
首先，从github上克隆本代码，使用以下命令：
git clone https://github.com/ZhangGongjie/Meta-DETR.git
