## Instrution

this package is extracted from Autoware.Auto

![image-20200122131803649](README/image-20200122131803649.png)

## Usage:

1. copy the package in your catkin workspace
2. in your launch file，add the following code

```xml
 <include file="$(find vehicle_description)/launch/lexus.launch"/>
```

3. in your rviz gui，you can add the RobotModel in the left

![image-20200315193039536](README/image-20200315193039536.png)