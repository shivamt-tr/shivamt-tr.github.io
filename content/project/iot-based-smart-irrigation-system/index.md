---
title: IoT-based Smart Irrigation System
date: 2023-11-08T18:12:18.133Z
summary: Simulated Arduino Mega 2560-based irrigation system on Wokwi, gathering temperature and humidity from DHT22 ssensors. Trained a neural network to predict water needs, whose flow is controlled via servo motors.
draft: false
featured: true
authors:
  - admin
tags:
  - iot
links:
  - url: https://github.com/shivamt-tr/IoT-based-Smart-Irrigation-System
    name: GitHub
    icon_pack: fab
    icon: github
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
<!-- # Training Section

## Training model on YOLOV7 based Architecture

Browse to YOLO Folder: 

```shell
cd yolov7
```

Basic Training Command:

```python
python train.py --data 'data/custom.yaml' --weights 'yolov7-tiny.pt'
```

To train on the yolov7-tiny architecture \[Leaky ReLu] :

```python
 python train.py --weights yolov7-tiny.pt --data data/custom.yaml --cfg cfg/final/OG/yolov7-tiny.yaml --device 0 --epochs 200 --name yolov7-tiny-pipe --hyp data/hyp.scratch.tiny.yaml
```

To train on the yolov7-tiny architecture \[Parametric ReLu] :

```python
python train.py --weights yolov7-tiny.pt --data data/custom.yaml --cfg cfg/final/yolov7-tiny-PRelu.yaml --device 0 --epochs 200 --name yolov7-tiny-prelu-pipe --hyp data/hyp.scratch.tiny.yaml
```

To train on the yolov7 + ecanet architecture :

```python
python train.py --weights yolov7-tiny.pt --data data/custom.yaml --cfg cfg/final/yolov7-tiny-ecanet-NO-SPPCSPC.yaml --device 0 --epochs 200 --name yolov7-ecanet-pipe-NS --hyp data/hyp.scratch.tiny.yaml
```

To train on the yolov7 + hornet architecture :

```python
python train.py --weights yolov7-tiny.pt --data data/custom.yaml --cfg cfg/final/yolov7-tiny-hornet2b-pipe.yaml --device 0 --epochs 200 --name yolov7-hornet-pipe --hyp data/hyp.scratch.tiny.yaml
```

To train on the yolov7 + ecanet architecture :

```python
python train.py --weights yolov7-tiny.pt --data data/custom.yaml --cfg cfg/final/yolov7-tiny-ecanet-NO-SPPCSPC.yaml --device 1 --epochs 200 --name yolov7-ecanet-pipe --hyp data/hyp.scratch.p5.yaml
```

## Training model on YOLOV5 based Architecture

Browse to YOLO Folder: 

```shell
cd yolov5
```

To train on the yolov5s:

```python
python train.py --weights yolov5s.pt --data data/custom.yaml --name yolov5s-pipe
```

To train on the yolov5n:

```python
python train.py --weights yolov5n.pt --data data/custom.yaml --name yolov5n-pipe
```

## Troubleshooting Training

To resume training (on failure):

```python
python train.py --weights runs/train/exp14/last.pt --resume
```

# Testing Section

## Detecting model on YOLOV7 based Architecture

To detect on video (Source: VIDEO):

```python
python detect.py --weights '../finalruns/yolov7-nano-hornet-ecanet-pipe/weights/best.pt' --img-size 640 --source ../testdata/test.mp4
```

To detect on video (Source: WEBCAM):

```python
python detect.py --weights '../finalruns/yolov7-nano-hornet-ecanet-pipe/weights/best.pt' --img-size 640 --source 0
```

# Model Section

## Final Declared Models

FINAL NANO MODEL:

```bash
../finalruns/yolov7-nano-hornet-ecanet-pipe2-1MB/weights/best.pt
```

FINAL TINY MODEL:

```bash
../finalruns/yolov7-tiny-hornet-ecanet-pipe2/weights/best.pt
```

# Model Architecture

## Original YOLOV7 Architecture

![Org Architecture](https://github.com/atanuroy911/CS776-DLCV-Project-IITK/raw/main/git-assets/images/Picture%203.png "Model Architecture")

## Modded YOLOV7 Architecture

![Moded Architecture](https://github.com/atanuroy911/CS776-DLCV-Project-IITK/raw/main/git-assets/images/Picture%201.png "Model Architecture")

# Testing Architecture

![Testing Architecture](https://github.com/atanuroy911/CS776-DLCV-Project-IITK/raw/main/git-assets/images/Picture%202.png "Comparison Between activation function vs mAP@50")

# Model Results

## Modded YOLOV7 Architecture Comparison

![Comparison](https://github.com/atanuroy911/CS776-DLCV-Project-IITK/raw/main/git-assets/images/Picture%204.png "Model Comparison")

## Modded YOLOV7 Architectiure Inference Times on Raspberry Pi

![Results](https://github.com/atanuroy911/CS776-DLCV-Project-IITK/raw/main/git-assets/images/Picture%205.png "Model Results Inference")
 -->