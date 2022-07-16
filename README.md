# Track and count vehicle using YOLOv5 and StrongSORT
- [AIC HCMC 2020](https://www.kaggle.com/datasets/hungkhoi/vehicle-counting-aic-hcmc-2020) dataset is used for detection training, further details are explained in the link below

<div align="center">
<a href="https://colab.research.google.com/drive/1ievillk4m2FIUwLw3dUyiORfdQzFLWg3?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Detection training in Google Colab"></a>
</div>

- Using [StrongSORT](https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet) algorithm, each vehicle is tracked frame by frame precisely
- Along with [author's original tracking code](https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet/blob/master/track.py), I also add object counting feature written in [track.py](https://github.com/nqa112/vehicle-tracking-counting/blob/master/main/Yolov5_StrongSORT_OSNet/track.py)
- Here is the code :
<div align="center">
<a href="https://colab.research.google.com/drive/1aq87w5hek9Isopgfc7WLYkKaLUUuecEb?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Tracking and Counting in Google Colab"></a>
</div>
