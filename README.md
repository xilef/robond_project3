# AMCL (Advanced Monte Carlo Localization)

Submission for Project 3 of the Udacity Robotics Software Engineer Nanodegree Program. This repository contains an additional amcl node to perform localization

## How to run

### Setup
Make sure you have gazebo and rviz installed and you have setup a catkin workspace

Clone the repo to your catkin workspace's src folder

eg:
`git clone https://github.com/xilef/robond_project3 /home/robond/workspace/catkin_ws/src
`

Go to the root of your catkin workspace and run `catkin_make` to build the whole repo

### Execute

When you open a new terminal make sure to run first `source devel/setup.bash` from the root of your catkin workspace.

Once all the setup is done run:

`roslaunch my_robot world.launch`

to load the world.

Open a new terminal, navigate to your catkin workspace and run:

`roslaunch my_robot amcl.launch`

to run the amcl node for localization

Once everything has loaded you can either try to send navigation goals via rviz or manually move the robot via the teleop package.
`rosrun teleop_twist_keyboard teleop_twist_keyboard.py`

## License

The content in this repository is free to use.
