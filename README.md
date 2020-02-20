# Custom version of BostonDynamics Spot robot

![Logo](https://gitlab.com/custom_robots/spotmicroai/website/raw/master/docs/assets/logo.png)

Project website: https://spotmicroai.readthedocs.io/en/latest/

# Assembly parts of SpotMicro project

Tip: Assembly.step file can be loaded in Autodesk Fusion 360

To save time I suggest you to use:
* Nozzle 0.6
* Contact Z distance for support materials 2mm
* Layer height 0.3 mm (50% of the nozzle size)

## Change Log

Version 1.03 - Febuary 20, 2020

All the following changes based in the Version 1.02

- Made the body 6cm longer
- Shoulders now symetricals and simple to unassemble for maintenance if needed, since they have the screws facing the user, in v1.02 for the rear shoulder was neccesary to unassemble the body to access the rear servos.
- Covers perimeters have been shorten 0.3mm, so the actuation/movement of the servos don't touch them.
- Foot has been improved, now is symetrical and has +1mm clearance for easy gluing.
- Added a support in the shoulders cables hole to avoid cables to be touching the legs as they move inwards to the body (till 35º max)

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
