# mecharm_270_ros2

This packages is built using robot description(URDF) provided by [elephant robotics](https://github.com/elephantrobotics/mycobot_ros2/tree/humble/mycobot_description/urdf)

## Download

```bash
git clone https://github.com/labiybafakh/mecharm_270_ros2
```

## Build
1. Before building the packges, several dependecies should be installed
```bash
rosdep install --from-paths src --ignore-src -r -y
```
2. Build the package 
```bash
colcon build --symlink-install
```

3. Source workspace
```bash
source install/setup.bash
```

## Run
```bash
ros2 launch mecharm_270_description mecharm_270.launch.xml
```

