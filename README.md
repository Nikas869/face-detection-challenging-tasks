# Comparison of different methods of face detection for difficult situations (Occlusion, scale, illumination etc.)

Dataset: 
[WIDER FACE](http://shuoyang1213.me/WIDERFACE/) divided on categories 
For each category manualy extracted 100 images to train

Compared face detectors:
* RetinaFace [Paper](https://arxiv.org/abs/1905.00641v2) [TF](https://github.com/peteryuX/retinaface-tf2) (based on RetinaNet)
* FaceBoxes [Paper]() [TF](https://github.com/TropComplique/FaceBoxes-tensorflow) (based on RPN)
* DFSD [Paper](https://arxiv.org/abs/1810.10220v3) [TF](https://github.com/610265158/DSFD-tensorflow) [PyTorch](https://github.com/TencentYoutuResearch/FaceDetection-DSFD) (based on VGG16)

Metrics:
* [mAP](https://medium.com/@jonathan_hui/map-mean-average-precision-for-object-detection-45c121a31173)
* FPS (ms)
