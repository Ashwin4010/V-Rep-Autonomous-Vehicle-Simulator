# V-Rep-Autonomous-Vehicle-Simulator with ROS


<img src="pictures/1.png"  >
<img src="pictures/gif1.gif"  >  
https://youtu.be/k36PovHUOAg  
  
  
<br /> <br />
## Instrunction
- It's built for Autonomous Vehicle Simulator using V-Rep & ROS simultaneously  
- It publishes data `Velodyne PointCloud`, `IMU Sensor`, `GPS`, `Localization (X,Y,Z,Heading)`, `Transform (tf)`  
to ROS at the same time as soon as you run the simulation.   
- Map File was built by using `Google Sketchup`.

1. move `libv_repExtImu.so`, `libv_repExtRosVelodyne.so` to your V-Rep home folder.  
2. open V-Rep 3.5 and Run `.ttt` file. if there is no error, It's OK  
  2.1. should USE `V-Rep 3.5` Version to use V-Rep with ROS automatically connected



<br /> <br />
## Topic 
<img src="pictures/2.png" width="400" >
<br /><br />

## Transform Tree(tf tree)
<img src="pictures/3.png"  >


<br /> <br />
## Reference
I've used IMU Plugin & Velodyne Plugin from   
https://github.com/bartville/vrep_plugin_imu  
https://github.com/omcandido/vrep_plugin_velodyne
<br /><br />

<br /> <br />
## TODO
1. Modify Vehicle Wheel 
2. Other Map (Highway, Urban etc..)
3. Use urdf file of Vehicle
4. Install other sensors on it


<br /> <br />
feel free to use and if you find any bug while using, post an issue. :-)  
