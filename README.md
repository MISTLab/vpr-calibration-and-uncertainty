This repo aims to calibrate Visual Place Recognition network to a target environment and provide uncertainty estimation. For more details look [our paper](http://arxiv.org/abs/2203.04446)

If you use the code in this repository please cite:
```
@article{lajoieCalibration2022,
	title = {Self-{Supervised} {Domain} {Calibration} and {Uncertainty} {Estimation} for {Place} {Recognition} via {Robust} {SLAM}},
	url = {http://arxiv.org/abs/2203.04446},
	doi = {10.48550/arXiv.2203.04446},
	year = {2022},
	author = {Lajoie, Pierre-Yves and Beltrame, Giovanni},
}
```

# How to use

- Use the `frame-extractor` to extract training samples from your data.
- Use the `vpr-and-uncertainty-calibrator` to calibrate your Visual Place Recognition network and train an uncertainty estimator.

See more execution details in the submodules.