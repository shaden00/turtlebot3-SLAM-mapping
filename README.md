**Launch navigation**

now it's time to navigate the map we created in slam [HERE](https://github.com/shaden00/Turtlebot3_Slam.git)
```
$ export TURTLEBOT3_MODEL=burger
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch
```

when gazebo is executed open a new terminal and run turtlebot3 navigation 
```
$ export TURTLEBOT3_MODEL=burger
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
```

**now you can see  RViz window with the map created earlier** [HERE](https://github.com/shaden00/Turtlebot3_Slam.git)




* Click the 2D Pose Estimate button in the RViz menu

<img width="574" alt="Screenshot_3" src="https://user-images.githubusercontent.com/97844314/183307173-6bbd9b6c-6e02-436f-bd4c-efda0c320f53.png">


* Click on the map where the actual robot is located and drag the large green arrow toward the direction where the robot is facing

* Move the robot back and forth a bit to collect the surrounding environment information and narrow down the estimated location of the TurtleBot3 on the map which is displayed with tiny green arrows


![image](https://user-images.githubusercontent.com/97844314/183307333-f92fd697-f2a3-448d-a542-cd8976b0f1af.jpeg)


![image](https://user-images.githubusercontent.com/97844314/183307348-28273a68-7211-41df-8329-7e19a63a4f04.jpeg)


![image](https://user-images.githubusercontent.com/97844314/183307362-dec214ea-454e-4d30-b7a8-85a0de583cb7.jpeg)


* Set Navigation Goal , Click the 2D Nav Goal button in the RViz menu


<img width="574" alt="Screenshot_4" src="https://user-images.githubusercontent.com/97844314/183307260-878b9d88-8088-495d-81a4-e3f9acc06f77.png">










**finally you will see turtle3 moving towards the destination**
















we have completed on reviewing how to teleoperate the turtle3 and run the navigation , please refer to the turtlebot3 manual for more details from [HERE](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/)
