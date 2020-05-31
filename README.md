# Computer_Vision
All the computer vision projects and experiments

## Kagle Setups
Setting up Google Colab to work seamlessly with Kaggle and it's datasets.
Two alternative ways are given in case one of the process fails

## Object detection
Object detection using different types of object detection algorithms using deep learning approaches.

### Using YOLO
YOLO model processes images in real-time at 45 frames
per second. A smaller version of the network, Fast YOLO,
processes an astounding 155 frames per second while
still achieving double the mAP of other real-time detectors. Compared to state-of-the-art detection systems, YOLO
makes more localization errors but is far less likely to predict false detections where nothing exists. Finally, YOLO
learns very general representations of objects.

[Click here!](https://pjreddie.com/media/files/papers/yolo.pdf)

### Using R-CNN
To bypass the problem of selecting a huge number of regions, Ross Girshick et al. proposed a method where we use selective search to extract just 2000 regions from the image and he called them region proposals. Therefore, now, instead of trying to classify a huge number of regions, you can just work with 2000 regions. These 2000 region proposals are generated using the selective search algorithm

[Click here!](https://arxiv.org/pdf/1311.2524.pdf)
