## setup

        sudo chmod -R 777 /dev/ttyUSB0

        code /home/ubuntu/.bashrc

### put into .bashrc

        alias asdf='source ./devel/setup.bash'
        alias mm='asdf; cd ~/catkin_ws; catkin_make'

        source /opt/ros/melodic/setup.bash
        source ./devel/setup.bash


## launch
        mm

        roslaunch my_dynamixel_tutorial controller_manager.launch
        
        roslaunch my_dynamixel_tutorial start_moveit_arm_controllers.launch

        rosrun lab3 cpp_file

