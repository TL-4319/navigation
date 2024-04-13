# This is a fork of Bolder Flight System navigation library.

Added features includes:
- EKF measurement update has option to fuse data from position only sensor i.e. Marvelmind beacons
- Moving baseline RTK sensor fusion i.e. uBlox F9P pairs. The implementation ultilizes the rover full 3D position relative to moving-base to resolve heading and tilt instead of using heading measurement from rover receiver. 
