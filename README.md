# [Knowledge Distillation approach towards Melanoma Detection](https://www.sciencedirect.com/science/article/abs/pii/S0010482522003730?via%3Dihub)

## Build a model with few parameters that can accurately detect Melanoma

This code is part of our paper titled *Knowledge Distillation approach towards Melanoma Detection* submitted in the Journal of Computers in Biology and Medicine (CIMB).

Full text of accepted version avaiable at [RG]().

Authors: **Md Shakib Khan**, Kazi Nabiul Alam, Abdur Rab Dhruba, Hasib Zunair, Nabeel Mohammed

**TL;DR** We propose a knowledge distillation based approach towards melanoma detection. The goal is build a model with few parameters that can accurately detect melanoma and can be easily integrated without requiring much compute. It enables us to build small and performant models which can be easily deployed in clinical settings without the need for heavy computational costs.

<img src = "https://github.com/Shakib-IO/KD-lesions/blob/main/figures/Dataset.png" width = "500">

## Major Requirements
This code requires

- Python: 3.7
- Tensorflow: 2.1.0
- Keras: 2.3.1
- OpenCV: 4.1.0

## Training and Testing
- Download the dataset from [drive](https://drive.google.com/drive/u/2/folders/1gxzsQ5QagPxtHXCJVfyaGvvJ3MV2nxXz) or [Gihub Releases](https://github.com/Shakib-IO/KD-lesions/releases/tag/V1.0)
- The [ISIC](https://www.isic-archive.com/#!/topWithHeader/onlyHeaderTop/gallery) Database.
- Load the dataset.
- Train the ```Teacher&Student``` Model.
- Run the pretrained models.

## Result
We report the training, testing time and accuracy on the ISIC test set.
<img src ="https://github.com/Shakib-IO/KD-lesions/blob/main/figures/Table%2002.png" width="800">

## Citation
If you use this code or models in your scientific work, please cite the following paper:

```
@article{KHAN2022105581,
title = {Knowledge distillation approach towards melanoma detection},
author = {Md Shakib Khan and Kazi Nabiul Alam and Abdur Rab Dhruba and Hasib Zunair and Nabeel Mohammed}
journal = {Computers in Biology and Medicine},
volume = {146},
pages = {105581},
year = {2022},
issn = {0010-4825}
}
```

