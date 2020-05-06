# Comparison of different methods of face detection for difficult situations (Occlusion, scale, illumination etc.)

Dataset: 
[WIDER FACE](http://shuoyang1213.me/WIDERFACE/) divided on categories 
For each category manualy extracted 100 images to train

Compared face detectors:
* RetinaFace [Paper](https://arxiv.org/abs/1905.00641v2) [TF](https://github.com/peteryuX/retinaface-tf2) (based on RetinaNet) [Review](https://towardsdatascience.com/review-retinanet-focal-loss-object-detection-38fba6afabe4)
* FaceBoxes [Paper](https://arxiv.org/abs/1708.05234) [TF](https://github.com/TropComplique/FaceBoxes-tensorflow) (based on RPN)
* DFSD [Paper](https://arxiv.org/abs/1810.10220v3) [TF](https://github.com/610265158/DSFD-tensorflow) [PyTorch](https://github.com/TencentYoutuResearch/FaceDetection-DSFD) (based on VGG16)
* SSD (mobilenet) [Paper](https://arxiv.org/pdf/1512.02325) [TF](https://github.com/yeephycho/tensorflow-face-detection) [Review](https://towardsdatascience.com/review-ssd-single-shot-detector-object-detection-851a94607d11)

[ResNet](https://towardsdatascience.com/review-resnet-winner-of-ilsvrc-2015-image-classification-localization-detection-e39402bfa5d8)
[VGGNet](https://medium.com/coinmonks/paper-review-of-vggnet-1st-runner-up-of-ilsvlc-2014-image-classification-d02355543a11)

Metrics:
* [mAP](https://medium.com/@jonathan_hui/map-mean-average-precision-for-object-detection-45c121a31173)
* FPS (ms)
