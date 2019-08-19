# 图像处理

想帮一个同事在用OSR识别图像中的数字时提高准确率，也对python的一些图像处理做了了解。单纯就色度、对比度、锐度的调整，已经能够让图像稍微清晰一点了，[RGB与视觉的关系本身就很有意思](https://www.zhihu.com/question/265265004)。

另外的一个想法是用KMeans减少图片的颜色，让背景与数字的对比更加清晰。

还有一类超分辨率的方法，用一些奇奇怪怪的神经网络，获得比原图像素更高的图像。实验了一下，在github上找了一个能在终端跑的项目[ESPCN-Tensorflow](https://github.com/drakelevy/ESPCN-TensorFlow) ，跑之前把类似的图片放入images文件夹内做训练集，可惜这个项目是python2的，很多包要再pip2一遍。

