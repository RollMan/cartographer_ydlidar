# YDLiDAR with cartograph
## Overview
This node conducts SLAM with YDLiDAR & visualize it in rviz. A map and trajectory can be showed.

## Author
Yohei Shimmyo <qwpmb554@gmail.com>

## Installation

```
catkin_make_isolated --install --use-ninja
```

## Usage

```
$ source install_isolated_setup.bash
$ roslaunch cartograph_ydlidar ydlidar.launch
# riz window will appear.
# Click 'ADD' of left pane.
# Click 'By Topic'
# Click '/map ---> Map' & OK
# Click 'ADD' of left pane.
# Click 'By Topic'
# Click '/trajectory_node_list  ---> MarkerArray'
```
