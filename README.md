# opencv-example

an open cv example from https://www.pyimagesearch.com/


run the follow command in your terminal, make sure all the files are in the same directory:

```
$ python real_time_object_detection.py \
	--prototxt MobileNetSSD_deploy.prototxt.txt \
	--model MobileNetSSD_deploy.caffemodel
```

if you are running this on raspberry pi, consider running the following command to make the video smoother:

```
$ python pi_object_detection.py \
	--prototxt MobileNetSSD_deploy.prototxt.txt \
	--model MobileNetSSD_deploy.caffemodel
```