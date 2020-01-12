# Samsung AI NYC Princeternship 2020
The code written for a five-day internship at Samsung AI, New York, NY. Our goal was to use inverse kinematics and computer vision to guide a 7-DOF robotic arm to pick up a ring, which we accomplished in four stages: 
1. The robotic arm can ''read'' its current position. If we manually guide the arm from a starting position to a ring, it can replay the trajectory. (No vision was used.) 
2. The robotic arm can use inverse kinematics (IK). If we give the robot a position in 3D realspace, it can adjust its joint angles to touch that position. (No vision was used.) 
3. The robotic arm can ''see'' locations via April tags. If we take one picture with an April tag on the arm, and an April tag on the ring, it can use computer vision (CV) and IK to touch the ring. 
4. The robotic arm can ''see'' locations via color segmentation and bounding boxes. If we take one picture with an April tag on the arm, and assume that the ring is a certain color, it can use computer vision (CV) and IK to touch the ring. 

In the last two stages, we had to transform between

Equipment list: 
- 7-DOF robotic arm with Dynamixel motors
- Blue ring (roll of masking tape, standard size)
- Red ring (small roll of tape)
- Shoe
- April tag fiducial markers
- Intel Realsense D435 camera (RGB-depth)


Authors: Ekin Gurgen, Ainil Norazman, Miguel Opena
