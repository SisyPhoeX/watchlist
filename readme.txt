——————————————————————————————————
关于一个python项目的虚拟环境：
尽管用pycharm创建新工程时虚拟已经自动建好了，但是由于有一些包无法通过pycharm来安装，只好在命令行里用
pip install package 来安装。此时就需要命令行处在已经激活的project/Scripts/env下
$ env\Scripts\activate
然而我的电脑在gitbash下由于未知原因无法激活虚拟环境，因此换用anaconda prompt
——————————————————————————————————
关于CSS样式：
Chrome浏览器会缓存CSS样式，所以每次测试时需按Ctrl+F5清除缓存