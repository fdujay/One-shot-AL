# One-shot-AL
- This repo provide some codes of one-shot active learning corresponding to paper:
[One-shot active learning for image segmentation via contrastive learning and diversity-based sampling](https://www.sciencedirect.com/science/article/pii/S0950705122000909).

- For your convenience, all the codes are released in jupyter format, providing some feature selection algorithms related with our paper.

- Note that the realize of self-supervised feature extraction is more complex,  but it's fortunate that many publicly available repos implement self-supervised feature extraction algorithms, such as contrastive learning as well as auto-encoders. And I highly recommend you refer to the repo: [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning).

- If you are interested in this topic, welcome to contact with me: 18111010004@fudan.edu.cn.

## Citation
```
@article{JIN2022108278,
title = {One-shot active learning for image segmentation via contrastive learning and diversity-based sampling},
journal = {Knowledge-Based Systems},
volume = {241},
pages = {108278},
year = {2022},
issn = {0950-7051},
doi = {https://doi.org/10.1016/j.knosys.2022.108278},
url = {https://www.sciencedirect.com/science/article/pii/S0950705122000909},
author = {Qiuye Jin and Mingzhi Yuan and Qin Qiao and Zhijian Song},
keywords = {Active learning, Contrastive learning, Image segmentation},
abstract = {Image segmentation tasks based on deep learning usually require a large number of labeled samples to obtain great performance of Convolutional Neural Networks (CNNs). However, even if samples are abundant, a major issue remains that labeling samples is usually time-consuming and costly. Active learning can select valuable samples for annotation, so as to reduce the annotation cost as much as possible while maintaining the performance of CNNs. Most existing active learning approaches work in an iterative way. However, this iterative scheme needs more interaction with experts, more labor and more computing resources. In this paper, we propose a one-shot active learning framework, i.e. Contrastive Annotation (CA) based on contrastive self-supervised learning and diversity-based query strategy, aiming to select valuable samples in one-shot. Extensive experiments on three segmentation datasets, i.e., skin lesion segmentation, remote sensing image segmentation and chest X-ray segmentation, show that our proposed CA framework outperforms state-of-the-art methods by large margins.}
}
```
