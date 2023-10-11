# Thermal range extrinsic calibration simulation environment

## gazebo simulation

you can get the simulation environment shown in the figure by running:

```ign gazebo school_and_wall_gazebo_world.sdf ```

![no_ray](https://github.com/allenthreee/thermal_extrinsic/blob/main/gazebo_simulation/extrinsic.png)
Click the three quotation marks in the upper right corner again, and search for lidar-> visualize lidar.
Then click pause in the lower left corner to start (the triangle inside the circle), and you can see the lidar ray.(再点一下右上角三个引号, 搜索lidar-> visualize lidar
然后再把左下角的暂停点成启动(圆圈里面的三角形)就可一看到 lidar ray了)
![ray](https://github.com/allenthreee/thermal_extrinsic/blob/main/gazebo_simulation/extrinsic2.png)

Then you can follow this [tutorial](https://gazebosim.org/docs/citadel/ros_integration) to convert ignition gazebo sensor info to ros_msg.

Here is [my own tutorial](https://zhuanlan.zhihu.com/p/657387526)

