# Depth_Estimation
 
The State of the Art of Depth Estimation from Single Images (SGDepth)
 

Self-supervised monocular depth estimation presents a powerful method to obtain 3D scene information from single camera images, which is trainable on arbitrary image sequences without requiring depth labels, e.g., from a LiDAR sensor. self-supervised semantically-guided depth estimation (SGDepth) method to deal with moving dynamic-class (DC) objects, such as moving cars and pedestrians, which violate the static-world assumptions typically made during training of such models
![1_Ej4JSOb-rHVHuhT-AhXcmw](https://github.com/user-attachments/assets/c8acd6c1-ed49-457e-8b68-190027ff369c)

This is the case for monocular depth estimation, where the goal is to help the computer understand the depth of images and predict how far scene elements are for each pixel of a single image.
![image](https://github.com/user-attachments/assets/2c13bb31-4e3e-4c12-a801-de299c8b5679)

In monocular depth estimation, the goal is the generation of pixel-wise estimates (a.k.a. a depth map) of how far each scene element is from the camera.
Using SGDepth for Distance Evaluation:
We employed SGDepth to evaluate the distance of moving cars and pedestrians in autonomous driving scenarios. By combining depth estimation with object detection and tracking, we achieved precise real-time evaluation of spatial relationships between the self-driving car and surrounding objects, enhancing safety and efficiency on the road.

