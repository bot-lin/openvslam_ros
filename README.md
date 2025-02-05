# openvslam_ros

[OpenVSLAM](https://github.com/OpenVSLAM-Community/openvslam)'s ROS package.

## Subscribed topics

### monocular setup

- `camera/image_raw`

### stereo setup

- `camera/left/image_raw`
- `camera/right/image_raw`

### RGBD setup

- `camera/color/image_raw`
- `camera/depth/image_raw`

## Published topics

- `~/camera_pose`

## Parameters

- `odom_frame`
- `map_frame`
- `base_link`
- `camera_frame`
- `publish_tf`
- `transform_tolerance`
- `use_exact_time` (stereo, RGBD only)

## Tutorial

Users unfamiliar with docker, ROS2, or OpenVSLAM should refer to the [tutorial](/doc/tutorial.md).
