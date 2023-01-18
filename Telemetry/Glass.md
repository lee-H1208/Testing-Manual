# Table of Contents
- [Introduction](#introduction)
    - [What is a Dashboard?](#what-is-a-dashboard)
    - [What is the difference between Dashboard and Glass?](#what-is-the-difference-between-shuffleboard-and-glass)
- [How does Glass work?](#how-does-glass-work)
    - [How do you open Glass?](#how-do-you-open-glass)
    - [Widgets](#widgets)
        - [Sendable Chooser](#sendable-chooser)
        - [PID Controller](#pid-controller)
        - [FMSInfo](#fmsinfo)
- [Procedures](#procedures)

<br />

# Introduction
Glass is a newly developed, experimental [dashboard](#what-is-a-dashboard) that supports many types of widgets. Some of these widgets are supported by the Simulation GUI, but there are some others, including:
1. [Sendable Chooser](#sendable-chooser)
2. [PID Controller](#pid-controller)
3. [FMSInfo](#fmsinfo)

In order to use Glass, robot code must be connected to the robot. More specifically, a connection must be established through NetworkTables, which is a protocal that transmits data to and from the robot.
    
Instructions to learn how to establish this connection can be found [here](https://docs.wpilib.org/en/stable/docs/software/dashboards/glass/networktables-connection.html).

## What is a Dashboard?
A dashboard is a visual representation of your data. 

Previously, we used shuffleboard, which is another dashboard that displays NetworkTables data and widgets that can be initialized and created by robot code.

## What is the difference between Shuffleboard and Glass?
Shuffleboard is more drive-team centric, meaning that it is a dashboard mainly used on the field during an actual competition game. 

Glass, on the other hand, is developed with programming debugging in mind. Several components of glass support this claim:
1. Command-Based Widgets
2. Viewing Robot Trajectories:
3. Viewing Robot Pose:

<br />
<br />

# How Does Glass Work?
## How do you open Glass?
A more detailed step by step instruction of how to open Glass is provided in the FRC docs. 
The link for that is [here](https://docs.wpilib.org/en/stable/docs/software/dashboards/glass/introduction.html).

## Widgets:
### Sendable Chooser
### PID Controller
### FMSInfo

<br />
<br />

# Procedures
