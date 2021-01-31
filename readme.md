# Caffe models of network in LocNet

<img src="https://github.com/ZJUYH/LocNet_caffe/blob/master/image/network.png" width= 1000>

The implementation of LocNet back-end is based on `caffe`, and this page contains the caffe models of LocNet network.

In the `models` folder, for example, `kitti_delta_range` means that this model is used in KITTI dataset with Velodyne HDL-64E, with the Δ-r representations.
The input of the network is the image-like representations of LiDAR data, which can be generated using [LocNet_frontend](https://github.com/ZJUYH/LocNet_frontend).

If you use our implementation in your work, please cite the following paper:

	@article{yin20193d,
	  title={3D LiDAR-Based Global Localization Using Siamese Neural Network},
	  author={Yin, Huan and Wang, Yue and Ding, Xiaqing and Tang, Li and Huang, Shoudong and Xiong, Rong},
	  journal={IEEE Transactions on Intelligent Transportation Systems},
	  year={2019},
	  publisher={IEEE}
	}

or other related conferences: 

	title={LocNet: Global localization in 3D point clouds for mobile vehicles}
	title={Efficient 3D LIDAR based loop closing using deep neural network}

If you have any questions, feel free to contact: [Huan Yin](https://yinhuan.site/) `zjuyinhuan@gmail.com`.
