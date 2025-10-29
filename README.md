Steps to run the package
------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------

Step1:- Unzip the pacckage in the source folder of your workspace
------------------------------------------------------------------------------------------
Step2:- Build the package using the command
        colcon build
------------------------------------------------------------------------------------------        
Step3:- Source the package in each terminal
        source install/setup.bash
------------------------------------------------------------------------------------------
Step4:- Export the turtlebot3 model in each terminal
        export TURTLEBOT3_MODEL=waffle_pi
------------------------------------------------------------------------------------------
Step5:- One terminal run the turtlebot3 gazebo simulation
        ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py
------------------------------------------------------------------------------------------
Step6:- In second terminal run the gesture node
        ros2 run tb3_gesture_control gesture_node
------------------------------------------------------------------------------------------
