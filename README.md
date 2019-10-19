# A Large-scale Attribute Dataset for Zero-shot Learning

<br>
<br>

<div align=center><img src="https://github.com/PatrickZH/A-Large-scale-Attribute-Dataset-for-Zero-shot-Learning/blob/master/Illustration.png"/></div>

<br>
<br>

We propose a Large-scale Attribute Dataset (LAD) which has 78,017 images of 5 super-classes, 230 classes. The image number of LAD is larger than the sum of the four most popular attribute datasets (AwA, CUB, aP/aY and SUN). 359 attributes of visual, semantic and subjective properties are defined and annotated in instance-level.
<br>
We organized an international Zero-shot Learning Competition under AI Challenger using this dataset. More than 110 teams attended the competition.
<br>
For fair comparison, we provide standard splits of classes for ZSL and splits of images for traditional supervised Learning (packaged in the data).
<br>
<br>
The links to download the paper, data, competition and baseline:

[paper download](http://openaccess.thecvf.com/content_CVPRW_2019/papers/MULA/Zhao_A_Large-Scale_Attribute_Dataset_for_Zero-Shot_Learning_CVPRW_2019_paper.pdf)

data download<br>
from [Google Drive](https://drive.google.com/open?id=1WU2dld1rt5ajWaZqY3YLwLp-6USeQiVG) <br>
from [BaiduYun](https://pan.baidu.com/s/1QpUpNLnUAOK1vhg5Di0qUQ), Password: cwju <br>

[competition link](https://challenger.ai/competition/zsl2018)

[baseline method](https://github.com/AIChallenger/AI_Challenger_2018/tree/master/Baselines/zero_shot_learning_baseline)

Citation <br>
```
@inproceedings{zhao2019large,
  title={A Large-scale Attribute Dataset for Zero-shot Learning},
  author={Zhao, Bo and Fu, Yanwei and Liang, Rui and Wu, Jiahong and Wang, Yonggang and Wang, Yizhou},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops},
  year={2019}
}
```
<br>
Experiment Details in the Paper <br>
We do separate experiments on each super-class. For each super-class, we do experiments for 5 times with different splits of seen/unseen classes. We provided the 5 splits in file "split_zsl.txt" (in the data package). For super-class X, e.g. F (Fruits), you can use all Label_F_xx in each Unseen_List, e.g. Unseen_List_1, as the testing unseen classes. The rest classes in super-class X are for training seen classes. The 5 Unseen_Lists are for 5 experiments, then the 5 results are averaged as the performance on super-class X. 
<br>
<br>
Contact: Bo Zhao (bozhaonanjing at Gmail)
