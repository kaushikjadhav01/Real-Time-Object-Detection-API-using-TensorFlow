# Real-Time-Object-Detection-API-using-TensorFlow
A <b>Transfer Learning</b> based <b>Object Detection API</b> that detects all objects in an image, video or live webcam. An <b>SSD</b> model and a <b>Faster R-CNN</b> model was pretrained on <b>Mobile Net COCO</b> dataset along with a label map in <b>Tensorflow</b>. These models were used to detect objects captured in an image, video or real time webcam. <b>OpenCV</b> was used for streaming objects and preprocessing.

# Screenshots
## Object Detection output for image using SSD
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_image_ssd.png">

## Object Detection output for video files using SSD
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_ssd_video1.PNG">
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_ssd_video2.PNG">

## Object Detection output for webcam using SSD
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_ssd_webcam.PNG">

## Object Detection output for image using Faster R-CNN
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_image_rcnn.png">

## Object Detection output for video files using Faster R-CNN
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_rcnn_video1.PNG">
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_rcnn_video2.PNG">

## Object Detection output for webcam using Faster R-CNN
<img src="https://github.com/kaushikjadhav01/Real-Time-Object-Detection-API-using-TensorFlow/blob/master/screenshots/output_rcnn_webcam.PNG">

# Technologies Used
<ul>
<li><a href="https://www.tensorflow.org/">TensorFlow</a></li>
<li><a href="https://keras.io/">Keras</a></li>
<li><a href="https://opencv.org/">OpenCV</a></li>
<li><a href="https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en_IN">IPWebcam</a></li>
<li><a href="https://www.python.org/">Python</a></li>
</ul>

# How to Install & Use
<ol>
<li>Install <b>TensorFlow Object Detection API</b> by following the instructions <a href="https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md">here</a></li>
<li>Download my repo and place the jupyter notebooks of my repo in models/research/object_detection folder of the Tensorflow API</li>
<li>Install <b>IPWebcam</b> app on your smartphone from app store</li>
<li>Open app and click on <b>Start Server</b></li>
<li>Replace the IP address in my jupyter notebooks with IP address in app on Smartphone and run the notebooks</li>
</ol>
