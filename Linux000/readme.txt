1. Windows应该是Win7以上系统，Bochs应安装在C:\Bochs，安装路径不要带有空格，否则出错。
注意：请将bochs的安装目录，加入到系统路径。

2. Linux下安装Bochs，下载源码包，上网上搜索安装教程。

3. 关于Bochs的配置文件，无需改动。
3.1 me.bxrc，双击可直接运行，打印A和B。
如需调试，可在命令行下，运行
bochsdbg -q -f me.bxrc
此时，可以进行命令行调试。

3.2 linux000_gui.bxrc 为另一配置文件，
可在windows下，运行图形调试界面，可双击Linux000.bat，或在命令行下，运行
bochsdbg -q -f linux000_gui.bxrc
此时，弹出图形调试界面。

4. Image为Linux 0.00源代码编译完的镜像文件，需要与me.bxrc放在同一目录下。

5. 目录Linux0.00源码内含源文件与编译文件，在新版Ubuntu下编译，需要修改原始的源代码，详见目录内的readme.txt




by Dr. GuoJun LIU
Last Updated On 2017-12-05
