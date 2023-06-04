# URDF Projects

Create ROS Package and Organize Robot Files

## Task1

create URDF files for designing a mobile robot(2/4-Wheels).

### Description

 This task involves setting up a ROS package and organizing the necessary files for a robot's description, including URDF, Gazebo configuration, and mesh files.

### Steps

1. Create a ROS package:

* Open a terminal and navigate to your ROS workspace directory.
* Execute the command `catkin_create_pkg my_robot_pkg` to create a new package named `my_robot_pkg` (replace `my_robot_pkg` with your desired package name).

2. Package Structure:

* Inside the `my_robot_pkg` package directory, create two folders: `urdf` and `mesh`.
* Command: `mkdir -p my_robot_pkg/urdf my_robot_pkg/mesh`

3. URDF Description:

* Create a file named `robot.xacro` inside the `urdf` folder.
* Add the necessary URDF code to define your robot's links, joints, and lidar.

Example structure:

```

<?xml version="1.0"?>
<robot xmlns:xacro="http://ros.org/wiki/xacro">
  <!-- Define robot links and joints -->
  <!-- Add lidar with .stl or .dae file -->
</robot>

```

4. Gazebo Configuration:

* Create a file named `gazebo.xacro` inside the `urdf` folder.
* Add the necessary Gazebo-specific code to control your robot and publish sensor data.
* Example structure:
  
```
<?xml version="1.0"?>
<robot xmlns:xacro="http://ros.org/wiki/xacro">
  <!-- Add Gazebo plugins for robot movement and sensor data publishing -->
</robot>

```

5. Material Definitions:

* Create a file named `material.xacro` inside the `urdf` folder.
* Define the `colors/materials` for different elements of your robot using the URDF material tag.
* Example structure:

```

<?xml version="1.0"?>
<robot xmlns:xacro="http://ros.org/wiki/xacro">
  <!-- Define colors/materials for robot elements -->
</robot>

```

6. Download Lidar Design Files:

* Visit a website where you can download the `lidar` design files in either `.dae` or `.stl` format.
* Save the downloaded files inside the `mesh` folder of your package.


## Task2

create URDF files for designing a mobile robot(2/4-Wheels) with adding a tower to the end of chassis the tower lenght must be at least 1 meter from the ground.

### Description

 This task involves setting up a ROS package and organizing the necessary files for a robot's description, including URDF, Gazebo configuration, and mesh files.

### Steps

1. Create a ROS package:

* Open a terminal and navigate to your ROS workspace directory.
* Execute the command `catkin_create_pkg my_robot_pkg` to create a new package named `my_robot_pkg` (replace `my_robot_pkg` with your desired package name).

2. Package Structure:

* Inside the `my_robot_pkg` package directory, create two folders: `urdf` and `mesh`.
* Command: `mkdir -p my_robot_pkg/urdf my_robot_pkg/mesh`

3. URDF Description:

* Create a file named `robot.xacro` inside the `urdf` folder.
* Add the necessary URDF code to define your robot's links, joints, and lidar.

Example structure:

```

<?xml version="1.0"?>
<robot xmlns:xacro="http://ros.org/wiki/xacro">
  <!-- Define robot links and joints -->
  <!-- Add lidar with .stl or .dae file -->
</robot>

```

4. Gazebo Configuration:

* Create a file named `gazebo.xacro` inside the `urdf` folder.
* Add the necessary Gazebo-specific code to control your robot and publish sensor data.
* Example structure:
  
```
<?xml version="1.0"?>
<robot xmlns:xacro="http://ros.org/wiki/xacro">
  <!-- Add Gazebo plugins for robot movement and sensor data publishing -->
</robot>

```

5. Material Definitions:

* Create a file named `material.xacro` inside the `urdf` folder.
* Define the `colors/materials` for different elements of your robot using the URDF material tag.
* Example structure:

```

<?xml version="1.0"?>
<robot xmlns:xacro="http://ros.org/wiki/xacro">
  <!-- Define colors/materials for robot elements -->
</robot>

```

6. Download Lidar Design Files:

* Visit a website where you can download the `lidar` design files in either `.dae` or `.stl` format.
* Save the downloaded files inside the `mesh` folder of your package.

`Note: Replace "my_robot_pkg" with your desired package name throughout the process.`

