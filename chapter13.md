#参数，打包，变量

在这次的练习中，我们将会使用更多的输入的方法，你可以使用他们把变量传递给脚本（脚本指的是你的.py文件）。你知道如何输入`python ex13.py`来运行ex13.py文件吗？ex13.py是这个命令的一部分，我们叫他为“参数”。我们现在做的是写一个脚本，然后也接受参数。

输入下面的程序，然后我会给你解释细节：

`from sys import argv
script, first, second, third = argv
print "The script is called:", script 
print "Your first variable is:", first 
print "Your second variable is:", second 
print "Your third variable is:", third`

在第一行，我们写了一个叫做`import`的东西。这就是我们如何在你的脚本中添加方法的方法。与其一次性给你所有的python的特点，python让你自己说自己打算用什么特点。这会让你的程序很精炼，而且它也会像其他程序员的文档一样，告诉他们你的代码是干嘛的。


