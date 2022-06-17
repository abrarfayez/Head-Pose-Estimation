# Head-Pose-Estimation

In this task, we want to know the Head’s pose from its translation and rotation 

# * Objective
Train 3 supervised machine learning models to predict the 3 euler angles; Pitch, Yaw and roll and project them on frames and images.

* features: Face landmarks (left eye, right eye, nose, left mouth, right mouth and chin) 
* labels: Pitch, Yaw and roll

# * Dataset
Dataset consists of 2000 image of different faces with different poses.

Dataset link: http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip 

# *Libraries used
* Mediapipe
* OpenCV
* sklearn
* Numpy

# *Model:
XGBOOST is used in prediction with: 
 * Pitch RMSE: 0.02774482498928444
 * Yaw RMSE: 0.03454617809222153
 * Roll RMSE: 0.03770939928977596
 																	 
