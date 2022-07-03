This repository "YOLOv5_custom" is based on the open-source yolov5 model, trained on a custom dataset. The yolov5 code, mostly references to ultralytics's repository [thanks to Ultralytics](https://github.com/ultralytics/yolov5).
# Sample running of this model
![](https://github.com/GulnazAleksashova/yolov5_custom/blob/master/4.jpg)
# Requirements
Python 3.8 or later with all requirements dependencies installed, including torch>=1.7. To install run:
```python
$ pip install -r requirements.txt
```
# Inference
`detect.py` runs inference on a variety of sources and saving results to `runs/detect`.
```python
$ python detect.py --source 0        --weights yolov5s_custom.pt # webcam      
                            file.jpg  # image 
                            file.mp4  # video                   
```

# Citation
yolov5 model [link](https://github.com/ultralytics/yolov5)
