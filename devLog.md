# MultiHeteroAgentExploration DevLog

Author: Sayantani Bhattacharya </br>
</br>
This DevLog documents the progress of the project, to keep track for me and as a reference to anyone else who wishes to work on something similar.

## Week2:

#### (a) Accomplishments
  1. Rviz simulation setup of go2 is working (ported from official ROS1 to ROS2).
  2. Got the merging map repository to work in my system.
  3. Gazebo setup for go1 and go2 working.
  4. 3D printed the Zed cam - Jetson - to go1 mount (modelling by [David Dorf](https://www.daviddorf.com/home)).
  5. Soldered the buck converter, jetson power and unitree (GO1) power ports: so the hardware setup for GO1 should be complete with this.

#### (b) Unresolved Problems:
  1. The Jetson I was using had the entire file system corrupted. Wasn't able to fix the issue, and am in the process of reconfiguring it. Waiting for the display port as well.
  2. Setting up Ethernet connection with go2 and my setup on my laptop.

#### (c) Plans: 
  1. Configure the Jetson.
  2. Get GO1 to perform a basic Navigation and map creation from slam task.
  3. Develop a simulation_navigation pkg to perform slam map creation and basic nav task, for both go1 and go2.
  4. Familiarize with the unitree_ros2 sdk for go2, and to get the system to work with ethernet.
  5. Start working on SLAM and Navigation nodes in the main repo.
  6. Get the simulation setup for GO2 done.

## Week1:

#### (a) Accomplishments
  1. Simulation setup of go1 is working.
  2. Simulation setup for go2 is ported to ROS2.
  3. Read and sorted a few research papers for map merging and collaborative SLAM. Trying to get a repository working for the same.
  4. Did basic movements in GO2 (via its App) to understand its operation.
  5. Developed an overview of the existing ROS packages for slam and navigation.

#### (b) Unresolved Problems:
  1. Simulation setup for go2 has some errors to be resolved.
  2. The map merging repository has some errors to be resolved.

#### (c) Plans: 
  1. Get the simulation setup for GO2 done.
  2. Complete GO2 hardware setup with Jetson Nano, Zed camera.
  3. Get it to perform a basic Navigation and map creation from slam task.
  4. Get the map merging repository to work.
  5. Start working on SLAM and Navigation nodes in the main repo.
