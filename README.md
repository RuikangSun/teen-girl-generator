运行代码：python main.py --input_height 256 --input_width 256 --output_height 64 --output_width 64 --dataset KaiFaZheZuiShuai --crop --train --epoch 300 --input_fname_pattern "*.jpg"



input_height与input_width后面的数字是输入图像的长宽，output_height与output_width则是输出图像，dataset后面的是文件夹data里训练图片的文件夹名称，epoch是迭代次数。
输出的图片和保存的模型在out文件夹里。


原作品：https://github.com/carpedm20/DCGAN-tensorflow

UP主再创作的作品：https://github.com/RuikangSun/teen-girl-generator

UP主个人空间：https://space.bilibili.com/32934057

演示视频：https://b23.tv/av56967234
[![Watch the video]](https://raw.github.com/GabLeRoux/WebMole/master/ressources/WebMole_Youtube_Video.png)](https://www.bilibili.com/video/av56967234)

需要的框架：
Python 2.7 or Python 3.3+
Tensorflow 0.12.1
SciPy
pillow
