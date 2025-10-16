# TurtleBot3 Dynamic Obstacle Navigation Study

## Objective
Test how TurtleBot3 with SLAM Toolbox and Nav2 handles dynamic obstacles in real-time:
- Can the robot detect moving obstacles?
- Does it modify the saved static map?
- How does the costmap layer respond to real-time changes?

## System Components
- TurtleBot3 Waffle Pi (simulation)
- SLAM Toolbox (localization mode with static map)
- Nav2 (navigation stack with costmap)
- Gazebo (simulation environment)
- RViz (visualization)

## Project Structure
- `config/` - Parameter files for SLAM, Nav2, and LIDAR
- `launch/` - Custom launch files
- `results/` - Experimental data and logs
- `docs/` - Research notes and findings

## Approach
1. Create static map with SLAM (120° FOV)
2. Switch to localization mode
3. Spawn dynamic obstacles
4. Observe costmap behavior
5. Document findings
# PCNC
