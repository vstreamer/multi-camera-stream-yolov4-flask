# multi-camera-stream-yolov4-flask
A Flask app for multiple live video streaming over a network with object detection, tracking (optional), and counting. Uses YOLO v4 with Tensorflow backend as the object detection model and Deep SORT trained on the MARS dataset for object tracking. Each video stream has an independent thread and uses ImageZMQ for asynchronous sending and process
