# GAN
此代码使用Context encoders对图像进行修复
1.训练 ：
    直接运行train.py
    其中model.py 存放的是生成模型和判别模型
    
2.测试：
   运行test.py  可测试多张图像，并将结果拼接起来
   运行test_one.py 可测试一张图像
3. 数据
     数据存放在dataset中
     目录结果如下
     --dataset
    --train  
        --paris #训练集的图片
    --val 
        --paris_eval_gt #验证集完整的图片
    --val_corrupted
        --paris_eval_corrupted #验证集缺失的图片

  
