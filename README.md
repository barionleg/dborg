# Custom version of BostonDynamics Spot robot

![Logo](https://gitlab.com/custom_robots/spotmicro/nvidia-jetson-nano/raw/master/docs/assets/logo.png)

BostonDynamics Spot robot: https://www.youtube.com/watch?v=wlkCQXHEgjA

Can you make it dance? join the challenge: https://www.youtube.com/watch?v=kHBcVlqpvZ8&list=PLp5v7U2tXHs3BYfe93GZwuUZLGsisapic&index=2

Original idea by KDY0523 https://www.thingiverse.com/thing:3445283

Some of the community videos: https://www.youtube.com/playlist?list=PLp5v7U2tXHs3BYfe93GZwuUZLGsisapic

* Join us in Slack: https://spotmicroai-inviter.herokuapp.com/
* Documentation: https://spotmicroai.readthedocs.io
* Forum http://spotmicroai.org/

This is the repository for Assembly parts of SpotMicro project.

In here you can find all the project repositories: **https://gitlab.com/custom_robots/spotmicro**

# Assembly parts of SpotMicro project

Assembly.step file can be loaded in Autodesk Fusion 360



## Change Log

Version 1.02 - September 23, 2019
- One model that supports servos from Hobbyking, Towerpro, or other high performance servos using standard metal servo horns. No more seperate models depending on which servos you have.
- adjusted wrist joint width to make up for 3dprinted flange for 5mm bearing
- Fixed hole size for captive nuts (again)

Version 1.01 - September 8, 2019
- Fixed hole size for captive nuts
- Screw holes for computer mount instead of extrusions

Version 1.00 - September 2, 2019
- Legs are now designated as Right or Left
- Body/Shoulders have been adjusted to facilitate left and right symmetry in the legs
- Captive nuts are used where possible
- Blank Nose and Black rear parts are included
- No need to reflect parts after download
- Chassis plate for RPi included
- Chassis plate for Jetson Nano included
- No holes cut in the covers
- STEP files added

Prior
- STL files
- Copy of Original SpotMicro Design
- Not complete
- MG996R Servo Horns from Hobbyking



## TODO

Rearrange the repo with the following structure to simplify

	Assembly/midleg/servo_size_xxx/horns
	Assembly/top_cover/plain
	Assembly/top_cover/lidar
