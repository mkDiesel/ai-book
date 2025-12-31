---
sidebar_position: 4
---

# Humanoid Modeling with URDF

This chapter covers how to model a humanoid robot using URDF.

## What is URDF?

URDF (Unified Robot Description Format) is an XML format for representing a robot model. URDF is commonly used in ROS to describe the physical properties of a robot.

## Core Components

### Links
A link is a rigid part of the robot. It has physical properties such as mass, and an inertia tensor.

### Joints
A joint connects two links together. It defines the kinematics and dynamics of how one link moves relative to another.

### Sensors
URDF can also describe the sensors on a robot, such as cameras and laser scanners.
