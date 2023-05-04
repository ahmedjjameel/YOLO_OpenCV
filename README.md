## Objected Detection based on YOLO and OpenCV


### 1. YOLO object detection in images

In this project, objected detection based on YOLO and OpenCV will be used to detect images and video streams using Deep Learning will be implemented using Python Programming. YOLO is trained on the COCO dataset. The COCO dataset consists of 80 labels, including, but not limited to:
People, Bicycles, Cars and trucks, Airplanes, Stop signs and fire hydrants, Animals, including cats, dogs, birds, horses, cows, and sheep, to name a few, Kitchen and dining objects, such as wine glasses, cups, forks, knives, spoons, etc. … and much more!
You can find a full list of what YOLO trained on the COCO dataset can detect using this [link](https://github.com/pjreddie/darknet/blob/master/data/coco.names).

        python yolo.py --image images/image_file_name.jpg
        
        
        
![street](https://user-images.githubusercontent.com/81799459/226161306-225e0a4f-0ba4-4249-a5c6-fae9ea7cfe9f.gif)


![2](https://user-images.githubusercontent.com/81799459/226163322-c72a5041-255a-4840-8aa9-fa8d3c4ee13c.gif)



### 2. YOLO object detection in video streams

        python yolo_video.py --input videos/video_file_name.mp4 --output output/video_file_name.avi --yolo yolo-coco
        


![ezgif com-video-to-gif](https://user-images.githubusercontent.com/81799459/226162430-19df3b94-be43-4292-ac55-07d84fa150f8.gif)



![ezgif com-video-to-gif](https://user-images.githubusercontent.com/81799459/226166537-cc098f4f-36f6-40f1-bd1e-d9188f1a21ae.gif)



### 3. Real-time object detection with deep learning and OpenCV

        python real_time_object_detection.py
        
        
        

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/81799459/226170172-59c0715f-41bd-4988-9834-939816dedd95.gif)



