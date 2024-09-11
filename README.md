# Football_Analysis System

## This project is about using machine learning, computer vision and deep learning to create a football analysis system. This project utilizes YOlO a state of the art object detector to detect the players, referees and footballs. It also utilizes trackers to track those object across frames. We also train our own object detector to enhance the output of the state-of-the-art models.  Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered.

## The main Features
### 1. Use ultralytics and YOLOv8 to detect objects in images and videos.
### 2. Fine tune and train your own YOLO on your own custom dataset.
### 3. Use KMeans to cluster pixles and segment players from the background to get the t-shirt color accurately. 
### 4. Use optical flow to measure the camera movement. 
### 5. Use CV2's (opencv) perspective transformation to represent the scene's depth and perspective. 
### 6. Measure player's speed and distance covered in the image. 