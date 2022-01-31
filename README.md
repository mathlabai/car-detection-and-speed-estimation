# To run the project:

1. Clone the repo with 
``` git clone https://github.com/mathlabai/car-detection-and-speed-estimation.git ``` in the terminal

2. Download yolo weights with running download_yolo_weights``` sh download_yolo_weights.sh ```
   or manually download and place weights in yolo-coco from https://pjreddie.com/media/files/yolov3.weights

3. Make sure you change the line of detection according to your video and fine tune the threshold and confidence for YOLO model

4. Run ```python detect.py -i video_01.mp4  -o out_video_01.avi -y yolo-coco ``` 