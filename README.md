# Multiple-Instance-Based-Video-Anomaly-Detection-Using-Deep-Temporal-Encoding-Decoding
Implementation of the paper "Multiple Instance-Based Video Anomaly Detection Using Deep Temporal Encoding-Decoding"
https://arxiv.org/abs/2007.01548.
The paper is accepted for publication in Expert Systems with Applications Journal 
I will keep update this page. I will upload the test model once the paper get published..-->

<p align="center">
<img src="https://github.com/AmmarKamoona/Multiple-Instance-Based-Video-Anomaly-Detection-Using-Deep-Temporal-Encoding-Decoding/blob/main/images/proposed_network.png" width="1024">
</p>

## Multiple-Instance-Based-Video-Anomaly-Detection-Using-Deep-Temporal-Encoding-Decoding Results and Comparisons

- AUC Performance on UCF-Crime
80.10 % AUC of the ROC curve
-Comparison provided against [Hassan et al.](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Hasan_Learning_Temporal_Regularity_CVPR_2016_paper.pdf), [Lu et al.](https://www.cse.cuhk.edu.hk/leojia/papers/abnormaldect_iccv13.pdf), [Sultani et al.](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sultani_Real-World_Anomaly_Detection_CVPR_2018_paper.pdf), [Zaheer et al.](https://sites.google.com/view/luv2020/talks/zaheer), [Zhong et al.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Graph_Convolutional_Label_Noise_Cleaner_Train_a_Plug-And-Play_Action_Classifier_CVPR_2019_paper.pdf), and [SRF](https://arxiv.org/abs/2008.11887).

<p align="center">
<img src="https://github.com/AmmarKamoona/Multiple-Instance-Based-Video-Anomaly-Detection-Using-Deep-Temporal-Encoding-Decoding/blob/main/images/AUC_UCF.PNG" width="650">
</p>


<p align="center">
<img src="https://github.com/AmmarKamoona/Multiple-Instance-Based-Video-Anomaly-Detection-Using-Deep-Temporal-Encoding-Decoding/blob/main/images/ROC_UCF_V4-1.png" width="650">
</p>

 AUC Performance on ShanghaiTech
  - 89.14 % AUC of the ROC curve
  - Comparison provided against [Zaheer et al.](https://sites.google.com/view/luv2020/talks/zaheer), [Zhong et al.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Graph_Convolutional_Label_Noise_Cleaner_Train_a_Plug-And-Play_Action_Classifier_CVPR_2019_paper.pdf),  and [SRF](https://arxiv.org/abs/2008.11887).
  
  <p align="center">
<img src="https://github.com/AmmarKamoona/Multiple-Instance-Based-Video-Anomaly-Detection-Using-Deep-Temporal-Encoding-Decoding/blob/main/images/AUC_Shang.PNG" width="650">
</p>

<p align="center">
<img src="https://github.com/AmmarKamoona/Multiple-Instance-Based-Video-Anomaly-Detection-Using-Deep-Temporal-Encoding-Decoding/blob/main/images/ROC_Shang_V4-1.png" width="650">
</p>

#Please cite the paper using the following 

@article{KAMOONA2023119079,
title = {Multiple instance-based video anomaly detection using deep temporal encoding–decoding},
journal = {Expert Systems with Applications},
volume = {214},
pages = {119079},
year = {2023},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2022.119079},
url = {https://www.sciencedirect.com/science/article/pii/S0957417422020978},
author = {Ammar Mansoor Kamoona and Amirali Khodadadian Gostar and Alireza Bab-Hadiashar and Reza Hoseinnezhad},
keywords = {Anomaly detection, Surveillance videos, Weakly supervised multiple instance learning},
abstract = {In this paper, we propose a weakly supervised deep temporal encoding–decoding solution for anomaly detection in surveillance videos using multiple instance learning. The proposed approach uses both abnormal and normal video clips during the training phase which is developed in the multiple instance learning framework where we treat the video as a bag and video clips as instances in the bag. Our main contribution lies in the proposed novel approach to consider temporal relations between video instances in a weakly supervised setting. We deal with video instances (clips) as sequential visual data rather than a set of independent instances. We employ a deep temporal encoding–decoding network that is designed to capture spatio-temporal evolution of video instances over time. We also propose a new loss function that maximizes the mean distance between normal and abnormal instance predictions. The new loss function ensures a low false alarm rate which is crucial in practical surveillance applications. The proposed temporal encoding–decoding approach with the modified loss is benchmarked against the state of the art. The results show that the proposed method performs similar to, or better than the state-of-the-art solutions for anomaly detection in video surveillance applications and achieves the lowest false alarm rate on UCF-Crime dataset.}
}
