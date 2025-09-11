This repository contains the latest revised versions of URDF and XML files for all robots (Mini Hi, Mini Pi plus, Mini Pi) of HighTorque Robotics, and will be updated continuously...

## Change Log

**2025.09.04**：Added the new hi_25dof XML file and fixed the left/right leg mass issue of pi_12dof.

![image-20250904181209991](./README.assets/image-20250904181209991.png)



**2025.09.03**：  Uploaded the 25-DOF URDF for Mini Hi (no XML file); uploaded the 24-DOF URDF for Pi Plus, with the XML file being 20-DOF.



**2025.08.28**：Set the initial position of Mini Pi to vertical.

For training, you can refer to the default position:

```python
    # Set default joint angles for the robot
    default_joint_angles = [
        -0.25,  # r_hip_pitch_joint
        0.0,    # r_hip_roll_joint
        0.0,    # r_thigh_joint
        0.65,   # r_calf_joint
        -0.4,   # r_ankle_pitch_joint
        0.0,    # r_ankle_roll_joint
        -0.25,  # l_hip_pitch_joint
        -0.0,   # l_hip_roll_joint
        0.0,    # l_thigh_joint
        0.65,   # l_calf_joint
        -0.4,   # l_ankle_pitch_joint
        0.0     # l_ankle_roll_joint
    ]

```





