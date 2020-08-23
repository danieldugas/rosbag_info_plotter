# rosbag_info_plotter

This tool plots the timings of messages in one or more rosbags.

![example screenshot](https://github.com/danieldugas/rosbag_info_plotter/raw/master/rosbag_info_plotter_example.png "example screenshot")


## Install

```
cd $YOUR_ROS_WORKSPACE/src
git clone git@github.com:danieldugas/rosbag_info_plotter.git
catkin build rosbag_info_plotter
```

## Usage

```
rosbag_info_plotter $MY_ROSBAG.bag --topics $TOPIC1 $TOPIC2
```

Arguments:

```
--topics
if left unspecified, 10 topics from the rosbag will be shown
```


