# THUman2.0 Dataset
### Function4D: Real-time Human Volumetric Capture from Very Sparse RGBD Sensors
Tao Yu, Zerong Zheng, Kaiwen Guo, Pengpeng Liu, Qionghai Dai, Yebin Liu.  CVPR 2021 Oral

[[Project Page]](http://www.liuyebin.com/Function4D/Function4D.html)
[[Youtube Video]](https://www.youtube.com/watch?v=-rWUn4fEQNU&t=90s)

![teaser](./THuman2.0.jpg)

NOTE: For privacy protection, please blur the faces if the images or the models appear in any materials that will be published (such as paper, video, poster, etc.)

### Agreement
1. The THUman2.0 dataset (the "Dataset") is available for **non-commercial** research purposes only. Any other use, in particular any use for commercial purposes, is prohibited. This includes, without limitation, incorporation in a commercial product, use in a commercial service, as training data for a commercial product, for commercial ergonomic analysis (e.g. product design, architectural design, etc.), or production of other artifacts for commercial purposes including, for example, web services, movies, television programs, mobile applications, or video games. The dataset may not be used for pornographic purposes or to generate pornographic material whether commercial or not. The Dataset may not be reproduced, modified and/or made available in any form to any third party without Tsinghua University’s prior written permission.

2. You agree **not to** reproduce, modified, duplicate, copy, sell, trade, resell or exploit any portion of the images and any portion of derived data in any form to any third party without Tsinghua University’s prior written permission.

3. You agree **not to** further copy, publish or distribute any portion of the Dataset. Except, for internal use at a single site within the same organization it is allowed to make copies of the dataset.

4. Tsinghua University reserves the right to terminate your access to the Dataset at any time.


### Download Instructions 
The dataset is encrypted to prevent unauthorized access.

Please fill the [request form](./THuman2.0_Agreement.pdf) and send it to Yebin Liu (liuyebin@mail.tsinghua.edu.cn) and cc Tao Yu (ytrock@126.com) to request the download link. 

By requesting for the link, you acknowledge that you have read the agreement, understand it, and agree to be bound by them. If you do not agree with these terms and conditions, you must not download and/or use the Dataset.


### Data Explanation
THuman2.0 Dataset contains 500 high-quality human scans captured by a dense DLSR rig.
For each scan, we provide the 3D model (****.obj) along with the corresponding texture map (material0.jpeg).

Update: THuman2.0 SMPL-X Paras.zip
We have released SMPL-X fitting results, you can download it from this repo directly. 
![image](https://github.com/ytrock/THuman2.0-Dataset/blob/main/THuman2.0%20SmplX.jpg)

### Related Datasets from THU3DV Lab [[Link]](http://liuyebin.com/)
[[MultiHuman Dataset]](https://github.com/y-zheng18/MultiHuman-Dataset/) Containing 453 high-quality scans, each contains 1-3 persons. The dataset can be used to train and evaluate multi-person reconstruction algorithms.

[[THuman Dataset]](https://github.com/ZhengZerong/DeepHuman/tree/master/THUmanDataset) Containing 6k (200 subjects x 30 poses) scans from a single RGBD sensor, with SMPL annotations. 



### Citation
If you use this dataset for your research, please consider citing:
```
@InProceedings{tao2021function4d,
title={Function4D: Real-time Human Volumetric Capture from Very Sparse Consumer RGBD Sensors},
author={Yu, Tao and Zheng, Zerong and Guo, Kaiwen and Liu, Pengpeng and Dai, Qionghai and Liu, Yebin},
booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR2021)},
month={June},
year={2021},
}
```

### Contact
- Tao Yu [(ytrock@126.com)](mailto:ytrock@126.com)
- Yebin Liu [(liuyebin@mail.tsinghua.edu.cn)](mailto:liuyebin@mail.tsinghua.edu.cn)
