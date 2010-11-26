ROS HRP-2 stack
===============

This stack contains packages specific to the HRP-2 robot.

It contains:
- launch files
- vision calibration files
- etc.

All HRP-2 launch files needs to know which model of HRP-2 you want to
use (i.e. hrp2_14, hrp2_10 or hrp2_simu). The ROBOT environment
variable is used to do so:

    $ ROBOT=hrp2_14 roslaunch hrp2_common main.launch
