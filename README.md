# Building-a-Map-Using-SLAM-Algorithm-with-TurtleBot3

This project is my last project in AI as an intern in Smart Methods, in this project I setup the PC to run TurtleBot3 in Gazebo simulation using ROS packages. These packages were tested under ROS melodic, ROS Development Studio.

# Install Dependent ROS 1 Packages

     $ sudo apt-get install ros-melodic-joy ros-melodic-teleop-twist-joy \
        ros-melodic-teleop-twist-keyboard ros-melodic-laser-proc \
        ros-melodic-rgbd-launch ros-melodic-depthimage-to-laserscan \
        ros-melodic-rosserial-arduino ros-melodic-rosserial-python \
        ros-melodic-rosserial-server ros-melodic-rosserial-client \
        ros-melodic-rosserial-msgs ros-melodic-amcl ros-melodic-map-server \
        ros-melodic-move-base ros-melodic-urdf ros-melodic-xacro \
        ros-melodic-compressed-image-transport ros-melodic-rqt* \
        ros-melodic-gmapping ros-melodic-navigation ros-melodic-interactive-markers
        
# Install TurtleBot3 Packages:

        $ sudo apt-get install ros-kinetic-dynamixel-sdk
        $ sudo apt-get install ros-kinetic-turtlebot3-msgs
        $ sudo apt-get install ros-kinetic-turtlebot3
        
# Set TurtleBot3 Model Name
        $ echo "export TURTLEBOT3_MODEL=waffle_pi" >> ~/.bashrc
Sometimes ROS is not configuring the the added files, so it is recommended to write this command:

        $ source ~/.bashrc
        
        
