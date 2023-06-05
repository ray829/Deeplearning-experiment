# Deeplearning test

## my-deeplabv3+

#### 实验一

1.**backbone**：resnet101，并且在resnet101中使用了动态路由
2.**优化器**：sgd
3.数据集：vaihingen256
4.batch-size：32，16

## deeplabv3+_origin

注：这是最原始的版本，没有对主干网络进行更改，做对比实验用

#### 实验一

1.**backbone**：xception，使用了动态路由
2.**优化器**：adam
3.数据集：vaihingen256
4.batch-size：32，16&emsp;注：不确定
实验结果：
<img src="images/deeplabv3+_origin1.png" style='zoom:70%'>

#### 实验二

1.**backbone**：xception，使用了动态路由
2.**优化器**：adam
3.数据集：cuiyusheng/postdam512
4.batch-size：12,&ensp;6
实验结果：
<img src="images/" style='zoom:70%' alt='还没运行结束'>

## deeplabv3+_test1

#### 实验一

1.**backbone**：xception，使用了动态路由
2.**优化器**：adam
3.数据集：vaihingen256
4.batch-size：32,&ensp;16（注：不确定）
实验结果：
<img src="images/deeplabv3+_test1_1.png" style='zoom:70%' alt=''>

#### 实验二

1.**backbone**：xception，使用了动态路由
2.**优化器**：adam
3.数据集：cuiyusheng/postdam512
4.batch-size：32,&ensp;16（注：不确定）
实验结果：
<img src="images/" style='zoom:70%' alt=''>