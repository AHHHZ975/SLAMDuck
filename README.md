# Project Overview
## Goal

- To explore the recursive Extended Kalman Filter (EKF) SLAM algorithm.

- This project involves hands-on robotics experience using a Duckiebot and a Duckietown.

## Hardware
### Duckiebot components

- Monocular camera.
- Raspberry Pi 3 for computation.

### Duckietown components

- Driveable surfaces and lane markings.
- Traffic signs and AprilTags for visual landmarks.

# Key Features

## SLAM Algorithm

- Focused on EKF-based SLAM.

- Used to estimate the trajectory of the Duckiebot and the map of the environment simultaneously.

## Data Acquisition

- Collected data from the Duckiebot's monocular camera and used Vicon data (ground truth) for comparison.

- The files are supposed to be uploaded soon (the repository may or may not include these datasets).


# Project Structure

The SLAMDuck project contains the following key files and directories:

1- ```slamduck.py, slamduck_v2.py, slamduck_v3.py```: 

- These appear to be the primary SLAM implementations, possibly evolving versions of the algorithm.


2- ```interpolate_velocity.py, monocular_duck.py, monocular_visual_duck.py, wheel_duck.py```: 

- Likely utility scripts or modules for specific components like velocity interpolation, monocular vision processing, and wheel data handling.

3- ```read_tags.py```: 

- Likely handles marker/tag detection for localization.

4- ```undistort_duckie_images.py```: 

- Suggests a preprocessing script to correct image distortions, essential for accurate SLAM.

5- ```my_node.py```: 

- Might define a ROS node or other execution entry point.
