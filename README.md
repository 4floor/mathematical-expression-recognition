# 基于端到端的深度学习算式识别模型CRNN（CNN+RNN）

## 数据集
项目中所使用的[数据集](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd009/MLND+Capstone/Mathematical_Expression_Recognition_train.zip)包含一个train.csv文件和10万张算式图片。每张算式图片包含一个算式等式（i.e. -2*(1+3)= -8），算式中可能包含+ - * 三种运算符和括号（，）以及等号=，数值为阿拉伯数字0-9。

## 运行环境

    * OS Ubuntu 18.04 LTS
    * CUDA, CUDNN  10.0, 7.4
    * Python 3.6
    * Jupter Notebook
    * TensorFlow 1.12.0
    * Keras 2.2.4
    * OpenCV 3.4.2
    * Pandas 0.24.1
    * Matplotlib 3.0.3
    
## 机器配置
		CPU：AMD R5 2600
		GPU：GeForce GTX 1070Ti (8GB)
		RAM：16GB

## 运行
    使用打开mathematical-expression-recognition.ipynb并运行，模型的训练在以上的机器配置下花费约5个小时，最终模型在测试集上对算式的识别的准确率为99.4%。