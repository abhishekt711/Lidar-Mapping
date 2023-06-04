# Lidar-Mapping


1) First Install ceres solver using this link http://ceres-solver.org/installation.html
2) install pcl using this http://www.pointclouds.org/downloads/linux.html
3) build mapping package using this following commands:

mkdir aloam


cd aloam


git clone https://github.com/abhishekt711/Lidar-Mapping/tree/main/src

cd ..

catkin_make


source devel/setup.bash



4) to create map
go to launch folder inside aloam_velodyne and check ur lidar model and write the filename.launch accordingly.

roslaunch aloam_velodyne filename.launch



the bag file for which u want to create the map play the filename.bah


rosbag play filename.bag



Thanks to aloam mapping package https://github.com/HKUST-Aerial-Robotics/A-LOAM





