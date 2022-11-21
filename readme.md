## setup

        sudo chmod -R 777 /dev/ttyUSB0

        code /home/ubuntu/.bashrc

### run

        echo -e "alias asdf='source ./devel/setup.bash'\nalias mm='asdf; cd ~/catkin_ws; catkin_make'\nsource /opt/ros/melodic/setup.bash\nsource ./devel/setup.bash\n" >> ~/.bashrc



## launch
        mm

        roslaunch my_dynamixel_tutorial controller_manager.launch
        
        roslaunch my_dynamixel_tutorial start_moveit_arm_controllers.launch

        rosrun lab3 cpp_file

