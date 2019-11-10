# Caffe models of network in LocNet

<img src="https://github.com/ZJUYH/LocNet_caffe/blob/master/image/network.png" width= 1000>

My implementation of LocNet is based on `caffe`, and this project contains the caffe models of LocNet network.

In the `models` folder, for example, `kitti_delta_range` means that this model is used in KITTI dataset with Velodyne HDL-64E, with the \Delta r representations.

Please cite:

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

The input of the network is the image-like representations of LiDAR data. I will open the front-end of LocNet in the future, which transforms the 3D LiDAR point cloud to 2D rotational-invariant features.

If you have any questions, please contact: [Huan Yin](https://yinhuan.site/) `zjuyinhuan@gmail.com`.
