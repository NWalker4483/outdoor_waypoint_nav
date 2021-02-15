```
- gps_waypoint to read the waypoint file, convert waypoints to points in the map frame and then send the goals to move_base

- gps_waypoint_continuous1 and gps_waypoint_continuous2 for continuous navigation between waypoints using two seperate controllers

- collect_gps_waypoint to allow the user to drive the robot around and collect their own waypoints

- calibrate_heading to set the heading of the robot at startup and fix issues with poor magnetometer data

- plot_gps_waypoints to save raw data from the GPS for plotting purposes

- gps_waypoint_mapping to combine waypoint navigation with Mandala Robotics' 3D mapping software for autonomous 3D mapping
```