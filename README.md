# image_filtering_for_aruco

[ROS](http://ros.org) package

Image filter for improving performance of aruco_mapping package

* Video: https://www.youtube.com/watch?v=fgW7b1jf4R8
* Author: [Jan Bacik] (http://www.smartroboticsys.eu/?page_id=895&lang=en), [Smart Robotic Systems] (http://www.smartroboticsys.eu)


## ROS API:

Subsrcibed topics: /camera/image_raw

Published Topics: /camera/image_raw_filtered

Parameters:

Name          | Type         | Value       | Comment                  |
------------- | -------------| ------------| -------------------------|
treshold      | int          | 0-255       |  0 means original image  | 
