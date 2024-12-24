### Point-Cloud-Aggregation-Based-on-GNSS-INS-Data-and-Moving-Object-Filtering
Data: 

A vehicle equipped with a top lidar, a GNSS-INS, and cameras is navigating through an urban environment. All sensors are intrinsically and extrinsically calibrated, time-synchronized, and supported by RTK correction data for GNSS accuracy. The collected sensor data is recorded and accessible for processing here. [Link Text](https://nuscenes.org/)


 

Tasks: 

1. Point Cloud Aggregation 

Using the provided calibration and ego-motion data from GNSS-INS, aggregate frame-by-frame lidar point data to create a comprehensive virtual point cloud representation of the environment along the vehicle's trajectory. 
 

2. Moving Object Filtering 

From the aggregated virtual point cloud, identify and remove data corresponding to moving objects to create a static representation of the environment. 
 

3. Point Cloud Colorization 

Enhance the static virtual point cloud by assigning color values to the points using image data from the cameras. This will result in a visually enriched, realistic representation of the environment. 



