# UbuntuAppPack
在乌班图系统下批量打包脚本相关资料
 Ubuntu-Linux环境下通过命令搭建android环境 通多ant脚本自动打包apk 具体细节可以看这篇博客。这些是一些相关的资料。
 http://blog.csdn.net/u012162503/article/details/51540024
 经过几天的试错！终于完成了在Ubuntu 环境下an自动化脚本打包apk。中间遇到各种坑。从最初开始吧！http://blog.csdn.net/xiaolei05/article/details/16872011 
这是我接触的第一篇对我帮助很大的博客文章。里面详细的介绍了Ubuntu下安装ant安装java jdk.我当时安装的是jdk8. 
一.安装jdk8 http://ubuntuhandbook.org/index.php/2015/01/install-openjdk-8-ubuntu-14-04-12-04-lts/ (源自这篇文章)

sudo add-apt-repository ppa:openjdk-r/ppa (打开终端的破折号或按Ctrl + Alt + T，当它打开时，运行下面的命令来添加PPA) 
2. . sudo apt-get update (在那之后，更新系统包缓存和安装OpenJDK 8) sudo apt-get install openjdk-8-jdk() 
3.sudo update-alternatives –config java (查看java英文信息) 
4.sudo update-alternatives –config javac(查看java中文 信息) 
5.java -version (查看java的版本信息)

如果运行和下面类似你的jdk8的环境配好了. 
openjdk version “1.8.0_01-internal” 
OpenJDK Runtime Environment (build 1.8.0_01-internal-b04) 
OpenJDK 64-Bit Server VM (build 25.40-b08, mixed mode) 等等。具体的可以去看博客，写的不好，有问题欢迎探讨。
