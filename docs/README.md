# DL2D3DReg

?> **DL2D3DReg**的全称是`Deep Learning 2D-3D Registration Framework`，通用深度学习2D-3D配准框架。其定义了四个基于深度学习的2D-3D图像配准基本模块，用于优化研究流程和快速上手2D-3D配准过程，省去重复造轮子的过程。

## 数据加载模块

加载体素文件，体素文件可视化，自动生成数据集。

!> 不需要生成训练数据的时候，记得修改`data_loader_config.toml`中的`is_load_voxel`、`generate_train_data`和`single_projection`都设置为0，再进行其他的设置。


## 模型定义模块

通过模块化的方式搭建网络，可以一次性搭建多个网络。

## 模型训练模块

## 结果评估模块