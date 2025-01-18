# MC_TP
TP of Mission Coordination
File containing code of catkin_ws part of code for controling 3 robots.

changes in original code:
- added - funcrion adjust_angle_to_flag(robot, flag_x, flag_y) using robot position and flag position for computations of angle to flag
- added - time planner, robots can start mission in diffrent time intervals in order to avoid colision
- added - speed regulation - robot is going to stop at the flag and also speed is linearly depend on the distance
- added - sonar function - if something is in specified range of sensor robot is going to stop and change trajectory until the path is clear
