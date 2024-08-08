# 人类视角下的园林设计分析
## 1. 图片的语义分割
### 1.1 训练ADE模型
#### 1.1.1 使用MXNET
通过MXNET可以直接获取相关模型进行语义分割
#### 1.1.2 使用PyTorch
使用PyTorch的方法详见[pytorch-deeplabv3plus-resnet101-ade20k](https://github.com/Sparrived/pytorch-deeplabv3plus-resnet101-ade20k)
### 1.2 使用ADE数据集训练的DeepLabV3-ResNet101模型对图片进行语义分割
#### 1.2.1 进行映射
通过type_f.json内的数据对模型结果进行映射
#### 1.2.2 获得数据
通过对映射后的数据进行解码，使用matplotlib进行绘图，得到最后的图示和数据表
