# anno_robot Project

## 简介
### 本工程为ROS下的一个机器人功能包，该机器人外观为一自主移动底盘，上载一六自由度机械臂，其功能包含运动学仿真、动力学仿真、自主导航等
## 依赖
### 本功能包依赖于完整的gazebo与moveit
## 使用
### 下载本功能包至工作区间的src目录下：
1. git clone https://github.com/ZSCwbx/anno_robot.git
### 至工作区间根目录分别执行catkin_make与source命令： 
1. catkin_make
2. source devel/setup.bash
### 测试各种功能
目前本功能包仍处于开发阶段，功能有限，后续功能将陆续开发并更新
1. rviz中查看机器人模型：roslaunch anno_description view_model.launch
2. gazebo中仿真：roslaunch anno_gazebo anno_gazebo.launch
3. 测试moveit功能：roslaunch anno_config demo.launch