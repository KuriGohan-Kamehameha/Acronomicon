List of files:
- ONICS.py - complete rework of Thien94's rs_to_mavlink.py script. Includes logging and thread management options.
- uplink.sh - bash script to manage LTE uplink. Supports self-recovery and includes a daily reboot at 1am to keep things fresh. Designed with the Sierra Wireless 340U in mind but may work with other modems as well. Remember to specify your APN.
- install_realsense.sh - untested script designed to fast-track installation of Intel's RealSense libraries. [Currently Untested]
- install_ros.sh - untested script designed to fast-track installation of ROS2 and realsense-ros. [Currently Untested]
- hall-monitor.sh - restarts any one service when it crashes.
- apriltags3.py - unmodified fork of the original work kept here as a dependency for t265_precland_apriltag.py
- t265_precland_apriltag.py - Optimized fork of Thien94's script of the same name. [Currently Untested]
