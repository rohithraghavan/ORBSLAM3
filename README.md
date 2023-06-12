# ORBSLAM3
Introduction to ORB Slam3

SLAM navigation helps in mapping while the vehicle is in an unknown environment.
ORB-SLAM comes from the fact that it uses Oriented FAST and Rotated BRIEF (ORB) features to detect and match key points in images. These features are combined with other techniques, such as loop closing and pose optimization, to achieve robust and accurate localization and mapping.
Monocular-Inertial ORBSLAM3 algorithm is being used.
Stereo-Inertial ORBSLAM3 algorithm is also being used
Plugins and Libraries used Pangolin, DBoW2,g20, Eigen3 

# Installation commands for ORB-SLAM 3 in Ubuntu 20.04

sudo apt-get install build-essential
sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev

sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libdc1394-22-dev libjasper-dev

sudo apt-get install libglew-dev libboost-all-dev libssl-dev

sudo apt install libeigen3-dev


