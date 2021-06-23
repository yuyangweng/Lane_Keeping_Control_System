# Lane Keeping System
The lane keeping system (LKS) is a key technique to Autonomous vehicles and plays an important role in staying safety. The lane keeping system (LKS) includes lane detection, lane tracking, and control that helps the driver keeping in maintaining safe travel within the marked lane of the road when the vehicle begins to move out of its lane. The lane keeping system can reduce the risk of lane departure effetely. This study presents the design and evaluation of lane keeping system (LKS). All simulation of the controller and the plant in this study was based on the developed model in SIMULINK environmen, and the system was built for a camera-based lane sensing system and steering wheel actuator. The control model uses the algorithm that combines data processing from lane keeping controller from the Model Predictive Control Toolbox and simulates in performance of the closed loop system.

![image](https://user-images.githubusercontent.com/85567441/123125171-dd5eac80-d47a-11eb-9981-6b9a6b8c41ab.png)


![image](https://user-images.githubusercontent.com/85567441/123124841-9a043e00-d47a-11eb-8fcd-84b2348a55b2.png)


An ego vehicle that has a lane-keeping system must have a sensor, such as a camera. The sensor measures the relative yaw angle and lateral deviation between the centerline of a lane and the ego car and measures the current lane curvature and curvature derivative. The lane keeping system adjusts the front steering angle of the ego car to keep the ego car traveling along the centerline of the lanes on the road, and the goal for lane keeping control is to minimize both lateral deviation and relative yaw angle.

