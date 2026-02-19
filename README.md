# Arena Mapping & Navigation System

Robotics project focused on building a fully autonomous mapping and navigation pipeline using sensor-based exploration and geometric reconstruction.

## Overview

The robot explores an unknown arena, records environmental data, reconstructs arena geometry using clustering algorithms, and navigates toward target AR markers.

This project combines robotics, geometry processing, and data science techniques.

## Key Concepts

- Autonomous mapping
- Odometry-based localization
- DBSCAN clustering
- Total Least Squares line fitting
- Deterministic navigation strategy

## Pipeline

Robot Exploration → Sensor Logging → Python Geometry Processing → Arena Reconstruction → Target Navigation

## Technologies

- LEGO NXT robotics
- NXC embedded programming
- Python
- NumPy
- DBSCAN clustering
- Geometric modeling

## Features

- Automatic arena boundary reconstruction
- Obstacle detection
- Navigation toward AR-tag targets
- Offline geometry extraction

## Results

The system reconstructs arena structure from raw sensor logs and produces deterministic navigation paths toward targets.

## Repository Structure

robot_code/ – Robot control logic  
python_pipeline/ – Mapping & geometry algorithms  
results/ – Generated maps and navigation outputs  
media/ – Experimental setup visuals  
report/ – Full technical documentation  

## Author

Ellen Habash  
Final-Year Computer Science Student — Robotics, Computer Vision & Autonomous Systems
