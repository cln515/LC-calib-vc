# LiDAR-camera calibration with variance cost

## Programs
+ Cariblation with variance cost
+ Frame-by-frame motion estimation (Pre-processing)
+ Fusion Bundle Adjustment (Pre-processing)

## Dependency

We tried in Windows10

- Eigen3 (https://eigen.tuxfamily.org/index.php?title=Main_Page)
- opengv (https://laurentkneip.github.io/opengv/)
- ceres (http://ceres-solver.org/)
- json perser (https://github.com/nlohmann/json)
- OpenCV 4.x (https://opencv.org/)
- dlib (http://dlib.net/)
- Point Cloud Library (http://unanancyowen.com/en/pcl181/)(Installer for Windows)
- cvl_toolkit (https://github.com/cln515/cvl_toolkit.git)
- camera_simulator (https://github.com/cln515/camera_simulator.git)

## run test

- download sample data ()
- replace the paths (<path/to/input> or <path/to/output>) in json files to your environments
- run frame-by-frame motion estimation with fbf_in.json as an argument (```$ framebyframe_motionest.exe fbf_in.json```)
- run FusionBA with ba_in.json as an argument (```$ fusionba.exe ba_in.json```)
- run calibration with direct_in.json as an argument (```$ LC-calib_vc.exe direct_in.json```)