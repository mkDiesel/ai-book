---
sidebar_position: 7
---

# Navigation with Nav2

This chapter covers Nav2 path planning concepts and navigation stacks for humanoids.

## Path Planning Concepts

Nav2 is the ROS 2 navigation stack, providing a flexible and configurable framework for autonomous navigation. It encompasses:
-   **Global Path Planning**: Determining a high-level, collision-free path from a start to a goal.
-   **Local Path Planning**: Generating short-term trajectories that avoid dynamic obstacles while following the global path.

## Navigation Stacks for Humanoids

Adapting Nav2 for humanoid robots involves specific considerations:
-   **Footstep Planning**: Instead of continuous motion, humanoid navigation often involves discrete footstep planning for stable bipedal locomotion.
-   **Balance Control**: Integrating balance control algorithms to maintain stability during movement.

## Bipedal Movement Considerations

When navigating with a bipedal robot, challenges include:
-   **Center of Mass (CoM) Management**: Ensuring the robot's CoM remains within its support polygon to prevent falling.
-   **Kinematic Constraints**: Accounting for the complex joint limits and movement capabilities of humanoid legs and arms.
