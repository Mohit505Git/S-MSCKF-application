# S-MSCKF-application
<br>
S-MSCKF from [https://github.com/KumarRobotics/msckf_vio](https://github.com/KumarRobotics/msckf_vio)

<br>

### Mainly focus on installation and explanation

<br>

### Install
~~~shell
 $ cd <workspace>/src && https://github.com/KumarRobotics/msckf_vio
 $ sudo apt-get install libsuitesparse-dev
 $ cd ~/<workspace> && catkin build msckf_vio -DCMAKE_BUILD_TYPE=Release
~~~

<br>

## Application 1 : Flight Goggles
### Setup
+ Refer the yaml files in [here](https://github.com/engcang/S-MSCKF-application/tree/master/flightgoggles)
+ Transformation between Cam and IMU(Body) is really important
+ IMU initialization buffer size increased in [here](https://github.com/engcang/S-MSCKF-application/blob/master/flightgoggles/msckf_vio.cpp)
+ The more precise calibrations of Cameras and IMU, the better performance

<br>

### Result Clip
