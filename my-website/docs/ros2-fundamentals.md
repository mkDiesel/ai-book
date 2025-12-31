---
sidebar_position: 2
---

# ROS 2 Fundamentals

This chapter covers the fundamentals of ROS 2.

## What is ROS 2?

ROS 2 is a set of software libraries and tools that help you build robot applications. It is a complete rewrite of ROS 1, designed from the ground up to be more robust, secure, and easier to use.

## Core Concepts

### Nodes
A node is a process that performs computation. In ROS 2, a robot system is comprised of many nodes that communicate with each other.

### Topics
Topics are named buses over which nodes exchange messages. Topics have anonymous publish/subscribe semantics, which decouples the production of information from its consumption.

### Services
Services are another way for nodes to communicate with each other. Services are based on a request/reply model, and are best used for remote procedure calls.
