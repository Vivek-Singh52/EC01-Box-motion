# EC01-Box-motion
Here I have included the workspace directory that I have created to achieve the motion of cube (forward and backward) and the video showing the simulation.

sdf file includes the world and models, also the plugins that are required. Models consist of a simple box and a reaction wheel (cylinderical disc) present at its center. It also includes code for the commands to control the motion of wheel and box. 'w' key when pressed moves the wheel in anticlockwise-direction (forward motion) and 's' key when pressed moves the wheel in clockwise-direction (backward motion). Additionaly when 'b' key is pressed, the motion of the wheel stops.

To open the gazebo based on this sdf file, a launch file is present that runs the command "ign gazebo robot.sdf". launch file is included in the ros package my_robot thus helping in ros2 implementations.
