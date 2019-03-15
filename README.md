# Forward Kinematics

Animating a walking skeletal rig using Quaternions to compute joint rotations.

## Languages Used

* C++

## Project Highlights

To see a project overview and to dive into the math, check out [Forward Kinematics](http://joshpatel.ca/forward_kinematics) at my portfolio [JoshPatel.ca](http://joshpatel.ca/).

## Getting Started

To view the source code and test the program, do the following:

* Download and install [Microsoft Visual Studio](https://visualstudio.microsoft.com/downloads/).
* Open the project solution:

```
CA1-ForwardKinematics\build\Forward Kinematics.sln
```

## Running The Program

To run the program within Visual Studio, click on:
```
Local Windows Debugger
```
To run the program without Visual Studio, run the exectuble:
```
CA1-ForwardKinematics\ResultDemo\Forward Kinematics.exe
```

If you see the following error:
```
Error MSB8036 The Windows SDK version 10.0.16299.0 was not found.
```
Go to:
```
Project->Properties->Configuration Properties->General->Windows SDK Version
```
Change the SDK version to your VS20\*\* SDK version.

## Demo

![demo](https://github.com/joshilp/joshilp.github.io/blob/master/images/CA1-ForwardKinematics/ca1.gif?raw=true)



## Authors

* **KangKang Yin** - *Initial framework and mocap data*