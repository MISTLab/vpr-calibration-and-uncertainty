This repo aims to calibrate Visual Place Recognition network to a target environment and provide uncertainty estimation. For more details look at [our paper](http://arxiv.org/abs/2203.04446).

If you use the code in this repository please cite:
```
@ARTICLE{lajoieCalibration2022,
  author={Lajoie, Pierre-Yves and Beltrame, Giovanni},
  journal={IEEE Robotics and Automation Letters}, 
  title={Self-Supervised Domain Calibration and Uncertainty Estimation for Place Recognition}, 
  year={2023},
  volume={8},
  number={2},
  pages={792-799},
  doi={10.1109/LRA.2022.3232033}}
```

# How to use

- Use the `frame-extractor` and `slam_interfaces` with ROS 2 to extract training samples from your data.
- Use the `vpr-and-uncertainty-calibrator` to calibrate your Visual Place Recognition network and train an uncertainty estimator.

See more execution details in the submodules.
