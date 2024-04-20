# Machine Learning for Robotics coursework project - Enhancing Social Distancing Compliance using YOLO 

## Team members
- M. VARUN REDDY 21BRS1507
- CHANAKYA SHIVAJI 21BRS1159
- SRI KRISHNA SANTOSH 21BRS1292

## SAMPLE OUTPUT
![image](https://github.com/MVARUNREDDY8203/ml_robotics_project/assets/94187286/e68cb62d-e39a-47ae-a79f-e42a20e0fcce)


## Note:
- to simulate the project in your local system, use the cmd `git clone https://github.com/MVARUNREDDY8203/ml_robotics_project.git` to clone repository to your local repository.
- download yolov3 weights or yolov3 tiny (will run on less capable systems but w lower accuracy) weights from https://pjreddie.com/media/files 
- `cd` to the project directory and then run `python social_distancing_analyser_2.0.py`
- change the `vname` variable to the name of the video for input stored under the `/videos` folder
- change the `angle_factor` variable to 1 as the camera view gets vertical and vice versa to 0
- under the `def_close()` function increase the values to be multiplied with `vc_calib_hor` , `vc_calib_ver` , `c_calib_hor` , `c_calib_ver` to increase the sensitivity/ reduce distance threshold for social distancing and vice versa, default values in comments. ![image](https://github.com/MVARUNREDDY8203/ml_robotics_project/assets/94187286/6e7f7c6d-2a8d-4d9e-87a2-7f58bf8533b8)



