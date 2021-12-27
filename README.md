1、用VS Code运行2048.py的时候发现两个问题并解决
（1）问题：连接Anaconda，运行Code后，无法找到第三方库curses，修改解释器、python path、添加环境变量等均没有用。
     解决方法：因为我的curses库安装在anaconda的新虚拟环境ann中，而VS Code无法在终端中激活新环境，只能用 Anaconda 自带的一个基础环境base，因此我把库重新安装在基础环境中就可以运行了。
（2）问题：运行Code后显示"python redirection is not supported"报错
     解决方法：不能用任何IDE来运行有curses包的python文件，所以用VS Code跑不起来，改用cmd或者Anaconda Prompt运行即可
     
    