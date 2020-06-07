# porosity_GAN
Application on microstructure in addictive manufacturing based CGAN  


1.数据集：非常抱歉，数据集暂时没有上传，因为还有一些其他基于这些孔隙图的工作还未发表，征求了导师意见后暂时先不上传，董老师如您有需要可以再联系我。
2.code使用torch写的。在GPU上安装tensorlayer时由于tensorflow版本问题未安装成功（当时GPU有其他同学跑tensorflow程序，所以没办法升级版本）决定用以前安装好的torch。
3.requirement：torch>=0.4.1
torchvision>=0.2.1

4.程序运行：code文件夹里有三种方法的文件夹：CGAN/DCGAN/LSGAN。每种方法文件夹内有一个.py文件和porosity_cGAN_results文件夹，porosity_cGAN_results文件夹内是运行结果。
直接运行即可。程序在spyder下完成，所以没有子文件
