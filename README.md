# ORBSLAM3
Introduction to ORB Slam3

SLAM navigation helps in mapping while the vehicle is in an unknown environment.
ORB-SLAM comes from the fact that it uses Oriented FAST and Rotated BRIEF (ORB) features to detect and match key points in images. These features are combined with other techniques, such as loop closing and pose optimization, to achieve robust and accurate localization and mapping.
Monocular-Inertial ORBSLAM3 algorithm is being used.
Stereo-Inertial ORBSLAM3 algorithm is also being used
Plugins and Libraries used Pangolin, DBoW2,g20, Eigen3 

# Installation commands for ORB-SLAM 3 in Ubuntu 20.04
```shell
sudo apt-get install build-essential
sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev

sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libdc1394-22-dev libjasper-dev

sudo apt-get install libglew-dev libboost-all-dev libssl-dev

sudo apt install libeigen3-dev
```
# Installation of OpenCV 4.4.0
First, make sure you have the latest software installed:
```
sudo apt-get update
sudo apt-get upgrade
```
Installing the Dependencies
```
sudo apt-get install build-essential cmake python3-numpy python3-dev python3-tk libavcodec-dev libavformat-dev libavutil-dev libswscale-dev libavresample-dev libdc1394-dev libeigen3-dev libgtk-3-dev libvtk7-qt-dev
```
Now, we install OpenCV
```
cd ~
mkdir Dev && cd Dev
wget https://github.com/opencv/opencv/archive/4.5.0.tar.gz
tar -xvzf 4.5.0.tar.gz
rm 4.5.0.tar.gz
cd opencv-4.5.0
```



