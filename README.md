# UM-Homo-Dataset

**UM-Homo-Dataset** provides some image pairs and feature point pairs on them for evaluating the accuracy of Homography matrix estimation.

The image data of **UM-Homo-Dataset** is collected by robots in real scenes, which have various lighting changes and dynamic objects.

**UM-Homo-Dataset** provides groundtruth feature point pairs that are preprocessed with SIFT and then manually selected, and each pair of images has ten pairs of relatively evenly distributed feature points.

## Dataset

Select about 500 image pairs from the raw data of **UM-CAD-Dataset**, mark the feature point pairs, and use it to evaluate the algorithm.

## Traditional Methods Leaderboard

- SIFT+RANSAC
- SIFT+MAGSAC
- ORB+RANSAC
- ORB+MAGSAC
- BEBLID+RANSAC
- BEBLID+MAGSAC
- ours

## Reference

- https://github.com/danini/magsac (Opencv?)
