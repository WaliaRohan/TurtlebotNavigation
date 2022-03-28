# TurtlebotNavigation
# The turtlebot3_nav_bringup
This catkin package contains launch files for the following - 

1. turtlebot3 gazebo simulations in different environments (including empty world, turtlebot3_world and house) with a custom rviz configuration
2. Launching AMCL module for turtlebot3
3. Launching gmapping module for turtlebot3
4. Launching move_base for turtlebot3 with dwa as the local planner and navfn global planner

It contains relevant yaml files including parameters required for successfully launching the modules above.

# turtlebot3_simulations
This package is included as a git submodule in this repository and is responsible for creating the simulation environment to be used by turtlebot3_nav_bringup. You can find this package at: https://github.com/ROBOTIS-GIT/turtlebot3_simulations.
