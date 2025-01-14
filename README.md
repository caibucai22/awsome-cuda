收集整理有关深度学习网络cuda加速的各种项目、脚本、代码（包括cuda前后处理，Tensort重写网络等，偏部署方向）

## CUDA-Learn-Notes

https://github.com/DefTruth/CUDA-Learn-Notes

一个cuda的学习仓库，收录了150+的kernel，包括了许多 transformer中使用的注意力模块加速实现；同时收录了 100+的 相关博客，包括 大模型、CV、推理部署加速。

作者还有许多其他优秀的相关工作【集中在大模型推理、diffusion推理等方面】，大佬！！！

值得学习！！！



## tensorrtx

https://github.com/wang-xinyu/tensorrtx

对经典的图像网络使用C++ Tensort Api进行了了重写，包括网络的权重加载，网络结构定义、构建 TensorRT 引擎，加载 TensorRT 引擎并运行推理

涉及的网络众多，如

- yolov3~yolov11

- unet
- detr、swin-transfommer

模型的前后处理多采用 cuda 进行加速，值得学习！



## Pointcept

https://github.com/Pointcept/Pointcept

实现并统一了众多的点云网络，其中涉及点云的耗时操作，使用cuda编写加速，并提供python接口调用

放在libs下

https://github.com/Pointcept/Pointcept/tree/main/libs 点击直达

涉及点云操作有

- grouping 聚类
- 插值
- 采样
- knnquery
- subtraction
- 注意力机制、相对位置编码rpe等



