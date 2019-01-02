# Trekking -  Computer vision training setup

This repository has configurations and scripts used for training the CNN model in the Trekking/Magellan project.

## Goals

* Keep scripts to download/upload labeled data
* Document past models and configurations tried by us
* Document changes done on top of vanilla models to suit our purpose

## Models

Keep this table in reverse chronological order (add new models **to the top**).

| Short name | Description | External reference | Configuration | Documentation |
|------------|-------------|--------------------|--------------|---------------|
| YOLO v3    | Detector using a single pass of a fully convolutional network | [YOLO: Real-Time Object Detection (v3)](https://pjreddie.com/darknet/yolo/) | [config/yolov3-tiny.cfg](config/yolov3-tiny.cfg) | [docs/yolov3-tiny.md](docs/yolov3-tiny.md) |
| YOLO       | Detector using a single pass of a fully convolutional network | [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolov1/) | [config/yolov1-tiny.cfg](config/yolov1-tiny.cfg) | [docs/yolov1-tiny.md](docs/yolov1-tiny.md) |
| DetectNet  | First model tried by us. Wasn't fast enough and never saw the light of day | [DetectNet: Deep Neural Network for Object Detection in DIGITS](https://devblogs.nvidia.com/detectnet-deep-neural-network-object-detection-digits/) |
