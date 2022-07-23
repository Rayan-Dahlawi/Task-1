# Task 1 Robotics and AI
### ROS Installation


In task 1, we should download Ubuntu 20.04 and install ROS Noetic by writing commands into the terminal in Linux operating system.

******

In the beginning, [download VirtualBox](https://www.virtualbox.org/wiki/Downloads). Then [download Ubuntu 20.04](https://releases.ubuntu.com/20.04/) to use Linux operating system. 

After that, install ROS Noetic by writing commands at Linux terminal . this is the commands of the installation:

```
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
```
sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
```
```
sudo apt-get update
```
```
sudo apt-get install ros-noetic-desktop-full
```
```
apt-cache search ros-noetic
```
```
source /opt/ros/noetic/setup.bash
```
```
echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
source ~/.bashrc
```
```
sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential
```
```
sudo apt install python3-rosdep
```
```
sudo rosdep init
rosdep update
```

To check if ROS installed or not: 



type this command:
```
roscore
```
