^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package automotive_navigation_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.0.2 (2018-08-08)
------------------
* Reorganized messages into renamed packages.
* Changed package name from module_comm_msgs to automotive_navigation_msgs.
* add RouteArray message to handle roads with more than one lane
* Fixing license in package.xml.
* Add ACC max distance in meters so that it can be displayed on shuttle GUI instead of just the 0 to 100% value on the existing highway autopilot GUI
* Add more lane styles to lane boundary message to support double lines
* Add lane boundary messages
* Add new message for velocity and acceleration that includes a calculated covariance
* Add Direction message from marti_localization_msgs
* Add ROS service to request map images
* Updating package.xml to format 2.
* Standardizing package.xml files.
* Version bump and minor formatting clean-up.
* Adding headers to some files that were missing them.
* Moving VelocityAccel to module_comm_msgs.
* Major package reorganization. See README for new package definitions.
* Contributors: Daniel Stanek, Joshua Whitley
