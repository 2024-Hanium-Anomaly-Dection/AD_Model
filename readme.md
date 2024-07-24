﻿## Anomaly Detection via Reverse Distillation
we develop Anomaly Detection via Reverse Distilation from [paper] (https://arxiv.org/abs/2201.10703)

1. Environment
    ```Shell
    pip install -r requirements.txt
    ```
2. Dataset
    > You should download MVTec from [MVTec AD: MVTec Software](https://www.mvtec.com/company/research/datasets/mvtec-ad/). The folder "mvtec" should be unpacked into the code folder.
3. Train and Test the Model
We have write both training and evaluation function in the main.py, execute the following command to see the training and evaluation results.
     ```Shell
    python main.py
    ```
    
 ## Reference
	@InProceedings{Deng_2022_CVPR,
    author    = {Deng, Hanqiu and Li, Xingyu},
    title     = {Anomaly Detection via Reverse Distillation From One-Class Embedding},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2022},
    pages     = {9737-9746}}