# Metu-navigation

```shell
roslaunch leo_gazebo leo_marsyard.launch
```

```shell
rosrun metu_navigation run.sh
```

OR

```shell
roslaunch rtabmap_ros rtabmap.launch rtabmap_args:= rgb_topic:=/zed2/left/image_rect_color depth_topic:=/zed2/depth/depth_registered camera_info_topic:=/zed2/depth/camera_info odom_topic:=/controllers/diff_drive/odom visual_odometry:=false frame_id:=base_link odom_frame_id:=odom approx_sync:=true rgbd_sync:=true
```

```shell
rosrun move_base move_base
```

```shell
roslaunch leo_viz rviz.launch
```
