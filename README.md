the Main Purpose of these Project is to Classifying images using deep learning and OpenCV . here i have implemented Python script that will use OpenCV dnn Module  and GoogleLeNet (pre-trained on ImageNet) to classify images.

# Realtime Object Recognition with Deep-Learning-OpenCV_3

Realtime object recognition using the OpenCV 3.3 dnn module + pretrained MobileNetSSD caffemodel.


## Installation
All the dependencies can be installed using `pip`. Just use the following command from the root directory of the project.
```bash
pip3 install -r requirements.txt
```

## How to run this script?
There are two options for video source:

 * Webcam
 * Android device running IP Camera (https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en)

To run the script using webcam as source :

```bash
python3 real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --source webcam
```

To run the script using IP Webcam as source, open the `real_time_object_detection.py` and edit the following line to match your host :

```python
host = 'http://192.168.0.101:8080/'
```

Then to run the script using IP as source :

```bash
python3 real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --source web
```

For any questions, create an issue in this repository.

Who made this
--------------

| <a href="https://github.com/VirgileDjimgou"><img src="https://avatars1.githubusercontent.com/u/8148300?s=400&v=4" alt="IoEngine" align="left" height="100" width="100" /></a>
|---
| [VirgileDjimgou](https://github.com/VirgileDjimgou)


Contribute
----------

1. Create an issue to discuss about your idea
2. [Fork it] (https://github.com/VirgileDjimgou/P156_Cartographie_Gmap_237)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create a new Pull Request
7. Profit! :white_check_mark:
