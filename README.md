# TREAD-ROS
Trajectory Racing Enhanced Application for Drones Robot Operating System

A custom wheeled robot in Gazebo's postoffice world. When the DRIVE button is pressed, the robot detects the RED gate, and drives toward it. Other functionality helps it get to its goal.

### Demo
#### Robot drives to goal: https://drive.google.com/file/d/1rYaJ3Cpv5fvkwflFxktoz0EMZJfkWf6i/view?usp=sharing

### Project Stack
Ubuntu18.04->Python2.7->OpenCV4.1.1->ROS Melodic->Gazebo9 (see tutorials, they are listed below)
<p align="center">
  <img width="460" height="300" src="/BotWaypointStack.PNG">
</p>

### :soon: How to run project
updated by 11 May 

## :soon: Current Functionality


| Bot can move  | Bot detects colour  | Bot detects distance |
| ------------- | ------------- | ------------- |
| :heavy_check_mark: Gazebo-Twist Integration  | :heavy_check_mark: Gazebo-OpenCV Integration  | :heavy_check_mark: Gazebo-LiDAR Integration  |
| :heavy_check_mark: Twist-ROS Integration  | :heavy_check_mark: OpenCV-ROS Integration  | :heavy_check_mark: LiDAR-ROS node Integration  |
| :heavy_multiplication_x: Action Server Integration  | :heavy_multiplication_x: Action Server Integration  | :heavy_multiplication_x: Action Server Integration  |
| :heavy_multiplication_x: SMACH Integration  | :heavy_multiplication_x: SMACH Integration  | :heavy_multiplication_x: SMACH Integration  |
| :heavy_multiplication_x: Virtualenv Integration  | :heavy_multiplication_x: Virtualenv Integration  | :heavy_multiplication_x: Virtualenv Integration  |

This is a SMACH state machine for the robot, it will be updated by 11 May.

![GitHub Logo](/images/state_machine.png)

## :soon: Contributions are welcome
2 May: Project will be usable by 11 May :sunflower:
See suggestions, then please contact me at thomaxarstens@gmail.com
- [x] Bot detects face on webcam and in world
- [ ] Bot detects hand gestures on webcam
- [ ] Bot detects Alpha Pilot obstacle
- [ ] Bot detects Unity3D Bot
- [ ] Bot detects position of object

### Official Changelog :sunflower:
https://trello.com/b/6ZOWkQXU/stage-dvic

![Changelog Board](/Changelog.PNG)

## The Steps to Usability

### Project security
:ballot_box_with_check: Upload project from ThomasCarstens PC

:ballot_box_with_check: Collaborators must fork https://github.com/AlphaPilotFrance/BotDrivestoWaypoint and contributions are merged by pull request.

### Project demo
:ballot_box_with_check: Can be demoed in 5min from ThomasCarstens PC but still needs work on...

:black_square_button: Integrating the workspaces

:black_square_button: Creating one launchfile

### Accommodating collaborations
:ballot_box_with_check: Clarity about areas that will benefit from contributions (see list above.)

:black_square_button: Github files are setup for any machine that runs Ubuntu 18.04.

:black_square_button: Run project in virtualenv ((steps to be determined))

:black_square_button: One tutorial for HOW to run project (virtualenv, command line)

:black_square_button: One tutorial for WHERE to add collaborations (project structure)

:black_square_button: One tutorial for HOW to collaborate (Github, Unit Tests e.g. does it work and does it integrate)

![GitHub Logo](/images/0NSBKZe.gif)



