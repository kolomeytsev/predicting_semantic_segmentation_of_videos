# predicting_semantic_segmentation_of_videos
Deep Learning project at Skoltech

In this project we focused on predicting future segmentations problem for different movable objects on the pictures. Several different approaches to this problem were investigated: predicting future segmentation based on the previous segmentations of the video, predicting frames based on the original frames and corresponding segmentations, adversarial networks to produce segmentation which ”looks almost like” a reasonable consequence to the given. For our models we used multi-scale architecture.

We test our models on [Davis](https://data.vision.ee.ethz.ch/csergi/share/davis/DAVIS-2017-trainval-480p.zip) and [CVPR 2018 WAD Video Segmentation Challenge](https://www.kaggle.com/c/cvpr-2018-autonomous-driving/data) datasets.

All models were implemented in Pytorch.

In this repository you can find the code for all models and several trained models.

### S2S
![Alt Text](https://media.giphy.com/media/1xm2oj27TxSLCsMd5l/giphy.gif)

![Alt Text](https://media.giphy.com/media/4T93vhNcbHIde1XWCV/giphy.gif)

### XS2S++
![Alt Text](https://media.giphy.com/media/1wptVmpFWb2TU9jmvJ/giphy.gif)

![Alt Text](https://media.giphy.com/media/mMEweeYfyByQ77lw3e/giphy.gif)
