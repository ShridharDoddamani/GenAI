# GenAI
Generate or create a robotic ARM by taking descrition of number of joints and links
## Features
- Generate 3D robotic arms based on number of joints/links
- Visualize kinematic structure in simulation tools like **CoppeliaSim**
- Supports various DOFs and joint types (revolute, prismatic)
- Easily extendable to integrate with ROS/MoveIt!

## Use Cases
- Educational demonstrations of kinematics
- Early-stage prototyping of robot manipulators
- Teaching inverse/forward kinematics with dynamic models

---

##  How It Works

1. **User Input**: Number of joints and links
2. **Generator Logic**:
   - Creates a model with revolute or prismatic joints
   - Assigns links, joint limits, masses
3. **Output**:
   - Generates a `.ttm` model file for CoppeliaSim
   - OR URDF for use in ROS (optional)

---
