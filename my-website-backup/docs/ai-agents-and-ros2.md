---
sidebar_position: 3
---

# AI Agents & ROS 2 Integration

This chapter covers how to integrate AI agents with ROS 2.

## The Perception-Planning-Actuation Flow

A common pattern in robotics is the perception-planning-actuation loop.
- **Perception**: The robot uses its sensors to perceive the world around it.
- **Planning**: The robot uses the perceived information to make a decision about what to do next.
- **Actuation**: The robot executes the decision by moving its actuators.

## Bridging Python Agents to Robot Controllers

We can use the `rclpy` library to write ROS 2 nodes in Python. This allows us to create AI agents that can communicate with the rest of the ROS 2 system. For example, an agent can subscribe to a topic with sensor data, process that data to make a decision, and then publish a message to a topic that controls the robot's actuators.
