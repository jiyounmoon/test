
# Termianl 1: Set Drone control <br>
- source setup_drone.bash  <br>
- roslaunch px4 posix_sitl.launch  <br>


# Termianl 2: Drone action interface <br>
- roslaunch redone_drone_control beyond_control_rosplan.launch  <br>


# Termianl 3: Ground robot action interface <br>
- CHECK drone's odometry topic: rostopic echo /mavros/local_position/odom  <br>
- roslaunch cm14 sim.launch  <br>


# Termianl 4 <br>
- roslaunch hait_demos strategic_tactical_redone_seperated_sim.launch  <br>


# Termianl 5 <br>
- rosrun rosplan_interface_strategic strategic_plan_redone.bash   <br>

