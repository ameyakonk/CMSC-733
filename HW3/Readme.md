# Structure from Motion
Affine structure from motion (SfM) is a computer vision technique that aims to reconstruct the 3D structure of a scene from a sequence of 2D images. The goal is to recover the 3D positions of the points in the scene, as well as the camera poses and intrinsic parameters.

Steps:
1.  Detected corners and used the second moment matrix to locate strong corners to use as keypoints.
2.  Programmed a Kanade-Lucas-Tomasi feature tracker from scratch to track a set of detected key points in an image over a sequence of images.
3.  Generated 3D points for the object by computing affine(motion) and 3D shape matrices from the tracked 2D keypoints.

## Results:
Following are the images of the detected keypoints in an image and the keypoints traversal in the sequence of images.
![sfm_hw](https://user-images.githubusercontent.com/78075049/222945669-23f47b40-8212-4d1e-8090-675d808dca2c.jpg)

Following is the image of the 3D point cloud generated from the sequence of points.
![3d](https://user-images.githubusercontent.com/78075049/222945754-830b907a-fd6d-41dc-81fe-eb21e9f7d2fc.png)



