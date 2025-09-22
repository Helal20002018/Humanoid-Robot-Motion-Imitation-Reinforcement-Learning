# Humanoid-Robot-Motion-Imitation-Reinforcement-Learning

Project Overview

This project was developed on the Ubtech Yanshee humanoid robot.
The focus was to enable the robot to mirror human upper-body movements using external camera measurements and to explore reinforcement learning (RL) for extending motion capabilities.

-- My Contributions

Human Motion Tracking: Designed a script to capture body dimensions (shoulder–elbow and elbow–wrist) from an external camera.

Motion Imitation on Yanshee: Developed control scripts to drive the robot’s servos so that it mirrors my own arm and head movements in real time.

Head Movement Replication: Implemented real-time tracking for left–right head rotations.

Accuracy Optimization: Achieved high precision in servo control to ensure the robot closely follows human motions.

Reinforcement Learning: Applied RL techniques to enhance motion performance and explore new movement behaviors.

Application-Oriented Design: Designed the system for scenarios where humans should avoid direct exposure (e.g., hazardous tasks), allowing the robot to act as a substitute.

-- Tools & Technologies

Frameworks: ROS / ROS 2, OpenCV

Simulation & Learning: Reinforcement Learning (RL)

Hardware: Ubtech Yanshee humanoid robot, external camera

Methods: Motion Imitation, Human-to-Robot Mapping, Servo Control, Reinforcement Learning

-- Outcome

Successfully achieved accurate real-time motion imitation from human to robot.

Enabled head and arm mirroring with precise servo synchronization.

Validated the system’s potential for remote task execution, where the robot substitutes for a human.

Explored reinforcement learning for extending movement capabilities beyond direct imitation.
