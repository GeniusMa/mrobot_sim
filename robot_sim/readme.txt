功能包
robot_description      机器人描述以gazebo仿真
robot_slam             机器人slam建图：使用gmapping算法
robot_nav              机器人自主导航
robot_teleop           机器人键盘控制功能包

常规功能

1.在rviz中仿真机器人 roslaunch robot_description arbotix_mrobot_with_laser_camera.launch
2.在gazebo中仿真机器人 roslaunch robot_description view_mrobot_with_camera_laser_gazebo.launch
3.slam建图 roslaunch robot_slam gmapping_demo.launch (可使用自建地图)
4.导航 roslaunch robot_nav robot_nav arbotiX_nav_demo.launch (可使用自建地图)
5.启动键盘控制节点 roslaunch mrobot_teleop.launch