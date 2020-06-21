# GAN_Understanding_Practicing

## [GAN Understand](./GAN_Understanding/README.md)

********

## GAN Practice

:shipit: :sparkles: :+1: :clap:

********

:lemon:  [**DCGAN**](https://arxiv.org/pdf/1511.06434.pdf)   :date:   2015

#### Loss Function 

- 【Binary_Cross_Entropy Loss】    
  
   <img src="./README/images/binary_crossentropy.png" height="50">
    
- 【Loss Function】    
  <!-- > ![CGAN loss](README/images/dcgan.png)  -->

   <img src="./README/images/dcgan.png" height="25">


#### Network 

   <img src="./README/images/dcganfull.png">

#### Implementation 
<!-- - ![tf1](README/images/tf1.png)  [DCGAN tensorflow Official](https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/generative/dcgan.ipynb) -->

- <img src="./README/images/pytorch.png" height="13">

- <img src="./README/images/keras.png" height="13">

- <img src="./README/images/tf1.png" height="13">

- <img src="./README/images/tf2.png" height="13">   


#### Reference 

- [DCGAN TensorFlow2.x Official](https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/generative/dcgan.ipynb)
- [DCGAN PyTorch](https://github.com/znxlwm/pytorch-MNIST-CelebA-GAN-DCGAN)

********

:lemon:  [**ConditionalGAN**](https://arxiv.org/pdf/1411.1784.pdf)   :date:    2014

- Log-Likelihood Estimates 对数最大似然估计
- Conditioning the model to direct the data generation process possibly 模型增加条件控制控制数据生成过程; conditioning based on class labels 条件控制是数据类别标签
- Probabilistic one-to-many mapping is instantiated as a conditional predictive distribution, the input is taken to be conditioning variable 输入条件变量可以实现一对多的条件生成分布,从而生成样本

#### Loss Function
- 【Loss Function】    
  
   <img src="./README/images/cganloss.png" height="13">

#### Network 

#### Implementation 

- <img src="./README/images/pytorch.png" height="13">

- <img src="./README/images/keras.png" height="13">

- <img src="./README/images/tf1.png" height="13">

- <img src="./README/images/tf2.png" height="13">   

#### Reference 

- [cGAN Keras: How to Develop a Conditional GAN (cGAN) From Scratch](https://machinelearningmastery.com/how-to-develop-a-conditional-generative-adversarial-network-from-scratch/)
- [cDCGAN Keras](https://github.com/gaborvecsei/CDCGAN-Keras)

********

:lemon:  **WassersteinGAN**   :date:    2017

#### Implementation 

- <img src="./README/images/pytorch.png" height="15">

- <img src="./README/images/keras.png" height="15">

- <img src="./README/images/tf1.png" height="15">

- <img src="./README/images/tf2.png" height="15">   

********

:lemon:  **InfoGAN**   :date:    2016

#### Implementation 

- <img src="./README/images/pytorch.png" height="15">

- <img src="./README/images/keras.png" height="15">

- <img src="./README/images/tf1.png" height="15">

- <img src="./README/images/tf2.png" height="15">   

********

:lemon:  **Self-Attention GAN**   :date:    2016



#### Network 



#### Implementation 
<!-- - ![tf1](README/images/tf1.png)  [DCGAN tensorflow Official](https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/generative/dcgan.ipynb) -->

- <img src="./README/images/pytorch.png" height="15">

- <img src="./README/images/keras.png" height="15">

- <img src="./README/images/tf1.png" height="15">

- <img src="./README/images/tf2.png" height="15">   


#### Reference 

- [DCGAN TensorFlow2.x Official](https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/generative/dcgan.ipynb)
- [DCGAN PyTorch](https://github.com/znxlwm/pytorch-MNIST-CelebA-GAN-DCGAN)


********

:lemon:  **Progressive Growing GAN**   :date:    2017



#### Network 



#### Implementation 
<!-- - ![tf1](README/images/tf1.png)  [DCGAN tensorflow Official](https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/generative/dcgan.ipynb) -->

- <img src="./README/images/pytorch.png" height="15">

- <img src="./README/images/keras.png" height="15">

- <img src="./README/images/tf1.png" height="15">

- <img src="./README/images/tf2.png" height="15">   


#### Reference 

- [DCGAN TensorFlow2.x Official](https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/generative/dcgan.ipynb)
- [DCGAN PyTorch](https://github.com/znxlwm/pytorch-MNIST-CelebA-GAN-DCGAN)

## Dataset

- [Kaggle - CelebA: 200k images with 40 binary attribute](https://www.kaggle.com/jessicali9530/celeba-dataset/data#)
- [CelebA in Google Drive](https://drive.google.com/drive/folders/0B7EVK8r0v71pWEZsZE9oNnFzTm8)

********

## Reference

- [Faster Guaranteed GAN-based Recovery in Linear Inverse Problems](http://www.ima.umn.edu/materials/2019-2020/SW10.14-18.19/28282/IMA2019_Computation_Imaging_Talk_Bresler_Slides.pdf)

- [Generative model](https://en.wikipedia.org/wiki/Generative_model)

- [Lecture 13: Generative Models](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture13.pdf)

- [Ian Goodfellow GANs PPT @ NIPS 2016](http://www.iangoodfellow.com/slides/2016-12-04-NIPS.pdf)
