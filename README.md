# MZ04-simulation-in-moveit
MZ04 model in moveit simulator  
run urdf demo:  
copy mz04 urdf folder into ~/catkin_ws/src  
under ~/catkin_ws  
catkin build  
source ~/devel/setup.bash  
roslaunch mz04 display.launch  
run moveit launch file:  
copy mz04_moveit_config folder into ~/catkin_ws/src  
under ~/catkin_ws  
catkin build  
source ~/devel/setup.bash  
roslaunch mz04_moveit_config demo.launch
