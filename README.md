Note: The issue with the Absolute Rotation action when multiple turtles are spawned has been fixed. To use teleoperation and the Absolute Rotation action with the second turtle, 
start the teleop node in the turtle's namespace:

ros2 run turtlesim turtle_teleop_key --ros-args -r __node:=nodename -r __ns:=/namespace

Replace namespace with the namespace of the turtle you want to control (for example, turtle2).
