<!DOCTYPE html>
<html>
<head>
	<title>Object Detection in Video using YOLOv3</title>
</head>
<body>
	<h1>Object Detection in Video using YOLOv3</h1>
  <p>This project aims to detect objects in videos using the YOLOv3 object detection algorithm.</p>

<h2>Dataset</h2>

<p>The dataset used in this project is a collection of videos with various objects in different settings. It includes both daytime and nighttime videos, as well as videos with varying weather conditions and object densities.</p>

<h2>Requirements</h2>

<ul>
	<li>Python 3.6 or higher</li>
	<li>OpenCV</li>
	<li>numpy</li>
	<li>matplotlib</li>
</ul>

<h2>Getting Started</h2>

<ol>
	<li>Clone this repository:</li>
<pre>
	git clone https://github.com/&lt;username&gt;/object-detection-in-video.git
</pre>

<li>Download the pre-trained weights for YOLOv3:</li>

<pre>
	wget https://pjreddie.com/media/files/yolov3.weights
</pre>

<li>Run the script to perform object detections:</li>

<pre>
	python object_detections.py --video &lt;path_to_video&gt;
</pre>

<p>The script will output a video with annotated frames showing the detected objects.</p>
</ol>

<h2>Customization</h2>

<p>You can customize the detection parameters by modifying the <code>object_detections.py</code> script. The following parameters can be adjusted:</p>

<ul>
	<li><code>CONFIDENCE_THRESHOLD</code>: Confidence threshold for detection (default: 0.5)</li>
	<li><code>NMS_THRESHOLD</code>: Non-maximum suppression threshold (default: 0.4)</li>
	<li><code>YOLOV3_CONFIG_PATH</code>: Path to YOLOv3 configuration file (default: yolov3.cfg)</li>
	<li><code>YOLOV3_WEIGHTS_PATH</code>: Path to YOLOv3 weights file (default: yolov3.weights)</li>
</ul>

<p>You can also experiment with different object detection algorithms or train your own model to improve the accuracy of the detections.</p>

<h2>License</h2>

<p>This project is licensed under the MIT License - see the <code>LICENSE</code> file for details.</p>
</body>
</html>
