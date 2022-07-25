# Mask Detection

## YOLOv7

Implementation a paper - [YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors](https://arxiv.org/abs/2207.02696)

## Installation

- [LINK](https://github.com/WongKinYiu/yolov7/blob/main/requirements.txt)

```python
!pip install -r requirements.txt
```


## Weight

![weight](./image/weight_pic.PNG)

- `YOLOv7-X` 사용



## Data

- [Kaggle_mask_detection](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection) 사용

### Data detail

```python
root
├──annotations (folder)
├  ├── maksssksksss0.xml
├  ├── maksssksksss1.xml
├  ├── maksssksksssn.xml
images (folder)
├  ├── maksssksksss0.png
├  ├── maksssksksss1.png
├  ├── maksssksksssn.png
└──dd.yaml
```

### Preprocessing

> `xml to txt`(추가 예정)



## Performance

### Training

![train_result](./train/results.png)

![train_pred](./train/test_batch1_pred.jpg)


### Test


![test_result](./test/confusion_matrix.png)


### Inference


![inference_result](./inference/12.png)


<iframe id="video" width="648" height="364.5" src="./inference/inference_video" frameborder="0">
</iframe>
