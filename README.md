# Manipulating-Turtles-using-Turtlesim-in-ROS2
ماقدرت اثبت البرنامج لان لاب توبي خرب 
بس كتبت الكود 
للتحكم بالسلحفاة
ros2 run turtlesim turtle_teleop_key
التلاعب 
ros2 service call /turtle1/teleport_absolute turtlesim/srv/TeleportAbsolute "{x: 5.0, y: 5.0, theta: 1.57}"
انشاء سلحفاه جديدة 
ros2 service call /spawn turtlesim/srv/Spawn "{x: 2.0, y: 2.0, theta: 0.0}"
