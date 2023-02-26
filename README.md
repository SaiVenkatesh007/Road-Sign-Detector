# Road Sign Detector

We can **detect** multiple types of **Road Signs** from the images using a pre-trained model named **YOLOv5 (You Only Look Once)**

This project is based upon **YOLOv5**.

---

* You can clone **YOLOv5** using

```
git clone https://github.com/ultralytics/yolov5.git
cd yolov5
pip install -r requirements.txt
```



* The dataset used to test the model is made by **Andrewmvd** (The images have been taken from there)

[https://www.kaggle.com/datasets/andrewmvd/road-sign-detection]()


* For changing the objects to be detected we can alter the function in preprocessing.py

```
def convert_voc_to_yolo():
	...
	# changing here will do
	names = ['trafficlight', 'speedlimit', 'crosswalk', 'stop']
```

---

#### Output sample
![1672019103234](https://user-images.githubusercontent.com/99477672/210702538-5e669b45-9836-4976-92e3-fbea0eba5f5a.png)


