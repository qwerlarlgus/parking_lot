# parking_lot
Object Detection: parking_lot

### object tracking
### https://www.youtube.com/watch?v=O3b8lVF93jU
### https://pysource.com/2021/01/28/object-tracking-with-opencv-and-python/

### YoloV5
##  !python train.py --img 320 --batch 16 --epochs 30 --data '../data.yaml' --cfg ./models/custom_yolov5s.yaml --weights yolov5s.pt --name yolov5s_results  --cache --hyp hyp.finetune.yaml
##  input image size 320
##  model yolov5s.pt - transfer learning   train.py: freeze = ['model.%s.' % x for x in range(24)]



### References
1. https://github.com/fabiocarrara/deep-parking

2. https://www.kaggle.com/blanderbuss/parking-lot-dataset

3. https://www.kaggle.com/ultralytics/yolov5-ultralytics - yolov5

4. https://github.com/ifzhang/FairMOT  - FairMOT

