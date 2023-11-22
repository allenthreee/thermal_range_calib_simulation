# Thermal range extrinsic calibration simulation environment

## gazebo simulation

you can get the simulation environment shown in the figure by running:

```ign gazebo school_and_wall_gazebo_world.sdf ```

![no_ray](https://github.com/allenthreee/thermal_range_calib_simulation/blob/master/images/extrinsic.png)
Click the three quotation marks in the upper right corner again, and search for lidar-> visualize lidar.
Then click pause in the lower left corner to start (the triangle inside the circle), and you can see the lidar ray.(再点一下右上角三个引号, 搜索lidar-> visualize lidar
然后再把左下角的暂停点成启动(圆圈里面的三角形)就可一看到 lidar ray了)
![ray](https://github.com/allenthreee/thermal_range_calib_simulation/blob/master/images/gazebo_2023_agu.png)

Then you can follow this [tutorial](https://gazebosim.org/docs/citadel/ros_integration) to convert ignition gazebo sensor info to ros_msg.

Here is [my own tutorial](https://zhuanlan.zhihu.com/p/657387526)

# ply/pcd convert

pcl_ply2pcd http://manpages.ubuntu.com/manpages/focal/man1/pcl_ply2pcd.1.html

pcl_pcd2ply http://manpages.ubuntu.com/manpages/focal/man1/pcl_pcd2ply.1.html

