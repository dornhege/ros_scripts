ros_scripts
===========

rosws_switch
------------
This script provides a shortcut when often working with multiple workspaces and switching between them.
Supports tab-completion!

    Usage: rosws_switch <workspace_name>

### Setup
Set the environment variable `ROSWS_HOME_DIR` to the directory containing ROS workspaces.
Source rosws_switch.complete in `.bashrc`.

Currently only supports a single directory.
Also assumes that `setup.bash` is in `<workspace_dir>/devel/setup.bash` for catkin workspaces.
