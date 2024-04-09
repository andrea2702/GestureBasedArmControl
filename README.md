# GestureBasedArmControl

## Overview

This ROS package allows you to control a robotic arm using hand and arm gestures detected with Mediapipe. With this package, you can interact with the robotic arm by performing various gestures such as hand movements and arm openings.

## Prerequisites

Before using this package, make sure you have the following installed:
- ROS (Robot Operating System)
- panda robot packages

## Installation

1. Clone this repository into your ROS workspace's `src` directory:
   git clone https://github.com/andrea2702/GestureBasedArmControl.git
   
2. Install the required dependencies by navigating to the scripts directory and running:
cd GestureBasedArmControl/scripts
pip install -r requirements.txt

## Usage
Run the hand arm control node:

rosrun GestureBasedArmControl main.py

## Demo
[![Demo del Proyecto](http://img.youtube.com/vi/9owxQ1zTffA/0.jpg)](https://www.youtube.com/watch?v=9owxQ1zTffA)
