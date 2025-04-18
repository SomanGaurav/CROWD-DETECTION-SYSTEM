# Crowd Detection System 
Crowd Detection System is a project that allows official for implementing crowd controls in specific areas through cameras . This project is especially usefoul in times when social distancing measusres are neccessary to stop the spread of corona virus . 
This system is opencv project that makes use of yolo models for detection of humans in it . 

### System Architecture 
- Crowd Detection System makes use of yolo models to map contour(rectangle) around humans in a the current video frame . Each contour is assigned a centroid .
- Distance between two contours is calculated using Euclidean Distance .
- If the distance value between the two contours is less than the threshold value crowd value is increase and they are mapped red on the frame . 

<p align="center">
  <img src="https://github.com/user-attachments/assets/0345c4c6-99e9-45a1-ab94-92abc95ac2c5"/>
</p>


### Yolo Model 
- Yolo which is abbreviation for you only look once is a neural network model used for object detection . As the name suggest this model requires only one forward pass for object detection .
