1、首先，通过命令行安装Python3.4，只需要在终端中通过命令行安装即可：
sudo apt-get install python3

2、刚才的Python3是被默认安装带usr/local/lib/python3.4目录中。

3、因为Ubuntu很多底层采用的是Python2.*，Python3和Python2是互相不兼容的，所以此时不能卸载Python2，需要将默认Python的指向Python3。现在在ubuntu中存在Python2和Python3.4两个版本：

1）如果不进行其他操作，在命令界面输入“Python”，将进入Python2版本的命令中；在命令界面输入“Python3.4”，将进入Python3.4版本的命令中；

2）如果将默认Python的指向Python3.4，即进行如下操作：

     首先，删除usr/bin/目录下的默认python link文件（即名字为Python的文件）。
     然后，打开终端输入如下命令行，建立新的连接关系： sudo ln -s /usr/bin/python3.4 /usr/bin/python
     最后，在命令界面输入“Python”，测试一下python版本是否正确
现在在命令界面输入“Python”，将进入Python3.4版本的命令中；在命令界面输入“Python2”，将进入Python2版本的命令中。
