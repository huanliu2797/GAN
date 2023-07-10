### 深度学习实践-基于python语言和PyTorch Code
##### 文件目录
- 卷积神经网络
  - 项目介绍：本项目是《深度学习实践-基于python语言和PyTorch》书籍中5.2：种植蔬菜种类识别与应用代码。本项目利用卷积神经网络对常见蔬菜进行种类识别。
  - 项目结构：
    1. 训练：直接运行vagetable_train.py文件即可训练
    2. 测试：直接运行vagetable_test.py文件即可测试
    3. 数据：数据存在datasets下，每种蔬菜一种文件夹，目录结构如下：
       - datasets
         - train  // 训练集
           - beetroot
           - bellpepper
           - cabbage
         - validation // 验证集
           - beetroot
           - bellpepper
           - cabbage
         - test // 测试集
- GAN 
  - 项目介绍：
  本项目是《深度学习实践-基于python语言和PyTorch》书籍中5.7 基于GAN的图像修复代码。GAN 是一种生成模型，随着GAN不断发展，各种GAN变体不断涌现，也在一些应用领域大放异彩。例如：图像生成、图像超分辨率重建、图像修复。本项目从图像修复的角度出发，利用经典的GAN修复图像模型-Context encoders，对图像缺失的地方进行补全。
  - 项目结构
    1. 训练： 直接运行train.py 其中model.py 存放的是生成模型和判别模型
    2. 测试： 运行test.py 可测试多张图像，并将结果拼接起来 运行test_one.py 可测试一张图像 
    3. 数据 数据存放在dataset中 目录结果如下 
       - dataset 
         - train 
           - paris  #存放训练集的图片
         - val 
           - paris_eval_gt  #存放验证集完整的图片
         - val_corrupted 
           - paris_eval_corrupted  # 存放验证集缺失的图片
    4. 结果 训练和测试的结果存放在result文件中