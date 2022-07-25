# taskAI_robot_arm

first i uave problem with the ros version i have installed so i installed a new version which is melodic and install new version of ubuntu which is ubuntu 18.04 then i create workspace with the following instruction 

$ source /opt/ros/melodic/setup.bash
$ mkdir catkin_ws
$ cd catkin_ws
$ mkdir src
$ cd src
$ catkin_init_workspace
$ cd ..
$ catkin_make
''
$ cd ~/catkin_ws/src
$ sudo apt install git
$ sit clone http://github.com/smart-methods/arduino_robot_arm
$ cd ~/catkin_ws
$ rosdep install --from-paths src --ignore-src -r -y
$ sudo apt-get install ros-kinetic-moveit
$ sudo apt-get install ros-kinetic-joint-state-publisher ros-kinetic-joint-state-publisher-gui
$ sudo apt-get install ros-kinetic-gazebo-ros-control joint-state-publisher
$ sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-ros-control
$ roslaunch robot_arm_pkg check_motors.launch
''
