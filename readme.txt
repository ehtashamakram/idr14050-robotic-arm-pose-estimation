- Extract the package to the catkin workspace, for a catkin workspace follow the instructions in this link https://wiki.ros.org/catkin/Tutorials/create_a_workspace.

- You are required to have MoveIt, for MoveIt you can follow the instructions on this link https://docs.ros.org/melodic/api/moveit_tutorials

- Source your catkin workspace using the command:
  catkin_make
  
- To start run the following command:
  roslaunch idr14050 gazebo.launch

  
- Launch rVis using the following command:
  roslaunch idr14050_moveit_config demo_planning_execution.launch

- Choose the world from fixed frame in rViz
  
- Run the following commands using a separate terminal:
  roslaunch idr14050 aruco.launch

- Run the following commands using a separate terminal:
  rosrun idr14050 ar.py


Follow the video for better guidance.  

  

