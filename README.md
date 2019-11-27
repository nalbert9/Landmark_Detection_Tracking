# Landmark Detection & Robot Tracking
This repository contains project files for Computer Vision, Nanodegree  via [Udacity](https://eu.udacity.com/course/computer-vision-nanodegree--nd891). It combine knowledge of robot sensor measurements and movement to create a map of an environment over time.

## Project Overview
There is a large variety of SLAM (Simultaneous Localization and Mapping) approaches available in the robotics community. Throughout this work we focus on *graph-based SLAM* approach, a robust method for tracking an object over time and mapping out its surronding environment, using elements of probability, motion models and linear algebra. 

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot.*

<p align="center">
	<img src="images/robot_world.png" align="middle" alt="drawing" width="500px">
</p>

## Project Structure
The project is structured as a series of Jupyter notebooks that are written in Python and designed to be completed in sequential order:

#### `robot_class.py`
__Notebook 1__ : Robot Moving and Sensing;

__Notebook 2__ : Omega and Xi, Constraints;

__Notebook 3__ : Landmark Detection and Tracking.

## Installation
```sh
$ git clone https://github.com/nalbert9/Landmark_Detection_Tracking.git
$ sudo pip3 install -r requirements.txt
```
## Results
**Robot:** 

 True last pose       | x=24.09 y=62.98      
 -------------------  |--------------------
 Predicted last pose  | x=23.45 y=64.13      


**Landmarks:**

 True Landmark        | [[22, 91], [3, 58], [76, 52], [73, 80], [49, 6]]                      
 -------------------  | ---------------------------------------------------------------------
 Estimated Landmarks  | [[21.8, 90.9], [3.1, 58.2], [76.2, 52.3], [73.4, 80.4], [49.1, 6.2]]  


## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
