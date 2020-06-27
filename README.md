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

# Technical Concepts
<b>Faster RCNN</b> is an object detection architecture presented by Ross Girshick, Shaoqing Ren, Kaiming He and Jian Sun in 2015, and is one of the famous object detection architectures that uses convolution neural networks like YOLO (You Look Only Once) and SSD ( Single Shot Detector).<br>
More information can be found <a href="https://towardsdatascience.com/faster-rcnn-object-detection-f865e5ed7fc4">here</a>
<br>
<br>
<b>Single Shot Detector (SSD)</b> like YOLO takes only one shot to detect multiple objects present in an image using multibox.
It is significantly faster in speed and high-accuracy object detection algorithm.<br>
More information can be found <a href="https://towardsdatascience.com/ssd-single-shot-detector-for-object-detection-using-multibox-1818603644ca">here</a>
<br>
<br>
<b>Label Maps:</b>  Cartographic labeling is the craft of placing text on a map in relation to the map symbols, together representing features and properties of the real world. Using text effectively creates maps that are clear, informative, and attractive. TensorFlow requires a label map, which namely maps each of the used labels to an integer values. This label map is used both by the training and detection processes.<br>
More information can be found <a href="https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html">here</a>
<br>
<br>
<b>An Inference Graph</b> is a propositional graph in which certain arcs and certain reverse arcs are augmented with channels through which information can flow – meaning the inference graph is both a representation of knowledge and the method for performing inference upon it. Channels come in two forms. The first type, i-channels, are added to the reverse antecedent arcs – named as such since they carry messages reporting that “I am true” or “I am negated” from the antecedent node to the rule node. Channels are also added to the consequent arcs, called u-channels, since they carry messages to the consequents which report that “you are true” or “you are negated.” Rules are connected by shared subexpressions.<br>
More information can be found <a href="http://www.cogsys.org/papers/2013poster15.pdf">here</a>
<br>
<br>
<b>Protocol Buffers (Protobuf)</b> is a method of serializing structured data. It is useful in developing programs to communicate with each other over a wire or for storing data. The method involves an interface description language that describes the structure of some data and a program that generates source code from that description for generating or parsing a stream of bytes that represents the structured data.<br>
More information can be found <a href="http://www.cogsys.org/papers/2013poster15.pdf">here</a>

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
<li>Install <b>TensorFlow API</b> by following the instructions <a href="https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md">here</a></li>
<li>Download my repo and place the jupyter notebooks of my repo in models/research/object_detection folder of the Tensorflow API</li>
<li>To use smartphone camera in place of laptop webcam, install <b>IPWebcam</b> app on your smartphone from app store. Open app and click on <b>Start Server</b></li>
<li>Replace the IP address in my jupyter notebooks with IP address in app on Smartphone and run the notebooks</li>
</ol>
