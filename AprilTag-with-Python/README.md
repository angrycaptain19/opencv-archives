# AprilTag-with-Python

## What is AprilTag
- Type of **fiducial marker**
- Consisting of a **black square with a white foreground** that has been 
generated **in a particular pattern**
- **Similar to a QR code — a 2D binary** However, an AprilTag **only holds 4-12** 
**bits of data, multiple orders of magnitude less than a QR code** (a typical QR 
code can hold up to 3KB of data)
- **so small, they can be more easily detected, more robustly identified, and** 
**less difficult to detect at longer ranges**
> if you want to store data in a 2D barcode, use QR codes. But if you need to 
use markers that can be more easily detected in your computer vision pipeline, 
use AprilTags
	
## AprilTag Properties

1. They are a square with binary values.
1. The background is “black.”
1. The foreground is a generated pattern displayed in “white.”
1. There is a black border surrounding the pattern, thereby making it easier to 
detect.
1. They can be generated in nearly any size.
1. Once generated, they can be printed out and added to your application.

## AprilTags Usability

1. Camera calibration
1. 3D applications
1. SLAM
1. Robotics
1. Autonomous navigation
1. Object size measurement
1. Distance measurement
1. Object orientation
1. ... and more!

## Examples use of AprilTag
1. A great example of using fiducials could be used in a large fulfillment 
warehouse (i.e., Amazon) where you’re using autonomous forklifts.
1. You could place AprilTags on the floor to define “lanes” for the forklifts 
to drive on. Specific markers could be placed on large shelves such that the 
forklift knows which crate to pull down.
1. And markers could even be used for “emergency shutdowns” where if that “911” 
marker is detected, the forklift automatically stops, halts operations, and 
shuts down.

## Installing the “apriltag” Python package
```
$ wget https://bootstrap.pypa.io/get-pip.py
$ sudo python get-pip.py
$ python -m pip install apriltag
```

## References
1. https://www.pyimagesearch.com/2020/11/02/apriltag-with-python/
