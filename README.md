# omo_r1mini

visit web site:

    https://omorobot.gitbook.io/manual/product/omo-r1mini/ros
    
    https://pinkwink.kr/1346
    
# Gazebo world

roslaunch omo_r1mini_gazebo omo_r1mini_empty_world.launch

roslaunch omo_r1mini_gazebo omo_r1mini_gazebo_rviz.launch

roslaunch omo_r1mini_gazebo omo_r1mini_turtlebot3_world.launch

roslaunch omo_r1mini_gazebo omo_r1mini_turtlebot3_house.launch


# simple_position_controller

roslaunch omo_r1mini_simple_position_controller simple_position_ctrl.launch

# teleop_key.launch

roslaunch omo_r1mini_teleop omo_r1mini_teleop_key.launch


# move 
rostopic pub /vanilla_position_controller/goal omo_r1mini_simple_position_controller/VanillaPositionActionGoal "header:
  seq: 0
  stamp:
    secs: 0
    nsecs: 0
  frame_id: ''
goal_id:
  stamp:
    secs: 0
    nsecs: 0
  id: ''
goal:
  x: 3.0
  y: 0.0
  theta: 0.0"
  

# rqt_garph

## rqt_plot

## rqt_multiplot
