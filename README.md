This repository is based on [pytorch-yolo-v3](https://github.com/ayooshkathuria/pytorch-yolo-v3)

# A PyTorch implementation of a DroNet Object Detector

## Requirements
1. Python 3.5
2. OpenCV
3. PyTorch 0.4

## Installation

```
sudo -H pip3 install torch==0.4.0
```

Using PyTorch 0.3 will break the detector.

## Running the detector

Clone, and `cd` into the repo directory. 

### DroNet_car

```
python3 video_demo.py --cfg cfg/DroNet_car.cfg --weights cfg/DroNet_car.weights --video Car_Parking.mov --classes 1
```

### DroNetV3_car

```
python3 video_demo.py --cfg cfg/DroNetV3_car.cfg --weights cfg/DroNetV3_car.weights --video Car_Parking.mov --classes 2
```

### DroNetV3_car

```
python3 video_demo.py --cfg cfg/DroNetV3_car.cfg --weights cfg/DroNetV3_car.weights --video Car_Crossroad.mp4 --classes 2 --reso 1024
```