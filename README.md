# NavIC-Robot


## To install Lidar ROS NODE

1. example, choose the directory name ros2_ws, for "development workspace" :

   ```bash
   mkdir -p ~/ros2_ws/src
   cd ~/ros2_ws/src
   ```

## Compile & Install rplidar_ros package

1. Clone rplidar_ros package from github

   Ensure you're still in the ros2_ws/src directory before you clone:

   ```bash
   git clone -b ros2 https://github.com/Slamtec/rplidar_ros.git
   ```

2. Build rpidar_ros package

   From the root of your workspace (ros2_ws), you can now build rplidar_ros package using the command:

   ```bash
   cd ~/ros2_ws/
   source /opt/ros/humble/setup.bash
   colcon build --symlink-install
   ```

   if you find output like "colcon:command not found",you need separate [install colcon](https://docs.ros.org/en/foxy/Tutorials/Colcon-Tutorial.html#install-colcon) build tools.

3. Package environment setup

    ```bash
    source ./install/setup.bash
    ```
