# R3BOT Warehouse Autonomous Mobile Robot (AMR)

![Project Logo]
<p align='center'>
<img width="95%" src="/img/1.png"/>
</p>

![Simulation ]
<p align='center'>
<img width="65%" src="/img/warehouse.gif"/>
</p>

![GUI]
<p align='center'>
<img width="65%" src="/img/gui_simulation.gif"/>
</p>



R3BOT is an advanced autonomous mobile robot designed for warehouse automation. This project leverages the Robot Operating System (ROS) to optimize material handling, enhance workplace safety, and increase operational efficiency.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Architecture](#architecture)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)


## Installation

### Prerequisites
- ROS Noetic
- Gazebo
- Python 3.8
- Tkinter
- PIL (Pillow)

### Step-by-Step Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/MohamedAwadin/R3BOT_Warehouse_Autonomous_Mobile_Robot-AMR-
   cd R3BOT_Warehouse_Autonomous_Mobile_Robot-AMR-
   ```

2. **Install dependencies:**
   ```sh
   sudo apt-get update
   sudo apt-get install ros-noetic-desktop-full
   sudo apt-get install python3-pip
   pip3 install rospkg catkin_pkg
   sudo apt-get install ros-noetic-gazebo-ros
   pip3 install pillow
   sudo apt-get install python3-tk
   ```

3. **Build the workspace:**
   ```sh
   cd ~/catkin_ws/
   catkin_make
   source devel/setup.bash
   ```

## Usage

### Running the Simulation
1. **Launch the Gazebo warehouse simulation:**
   ```sh
   roslaunch r3bot_simulation warehouse.launch
   ```

2. **Run the GUI for navigation:**
   ```sh
   roslaunch warehouse_simulation gui_warehouse_nev.py
   ```

### Adding Delivery Points
- Open the GUI.
- Enter the coordinates (X, Y) in the respective fields.
- Click on the "Add Point" button.

### Removing Delivery Points
- Open the GUI.
- Enter the index of the delivery point to be removed.
- Click on the "Remove Point" button.

## Features
- **Simulation Development:** Comprehensive warehouse simulation environment in Gazebo.
- **Autonomous Navigation:** ROS-based navigation algorithms for precise movement.
- **User Interface:** Intuitive GUI for managing robot tasks and monitoring status.
- **Real-time Data Collection:** Collects and analyzes data to optimize performance.
- **Enhanced Safety:** Reduces manual handling, enhancing workplace safety.

## Architecture
### Overview
- **Simulation:** Gazebo environment for testing.
- **ROS:** Core framework for robot operations.
- **GUI:** Developed using Tkinter for user interaction.
- **Navigation:** SLAM algorithms for real-time mapping and navigation.

### Components
- **Gazebo:** For warehouse simulation.
- **ROS Nodes:** For robot control and navigation.
- **Tkinter GUI:** For user interaction.

## Contact
**Mohamed Awadin**  
Email:    mohamedawadin01@gmail.com
GitHub:   [MohamedAwadin](https://github.com/MohamedAwadin)
LinkedIn: [MohamedAwadin](https://www.linkedin.com/in/mohamedawadin/)
