## setup

        sudo chmod -R 777 /dev/ttyUSB0
        

        code /home/ubuntu/.bashrc
        
        alias asdf='source /opt/ros/melodic/setup.bash; source ~/catkin_ws/devel/setup.bash'
        alias mm='asdf; cd ~/catkin_ws; catkin_make'



## launch
        roslaunch my_dynamixel_tutorial controller_manager.launch
        
        roslaunch my_dynamixel_tutorial start_moveit_arm_controllers.launch

        rosrun lab3 cpp_file

