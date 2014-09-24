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

这里的`argv`是一个“参数变量”，是一个在程序中十分标准的名字，你会在其他语言中用到的。这个变量是你运行python脚本的时候你传递的参数。在这个练习中，你将会看到更逗这样的内容然后查看效果是什么。

在第三行拆分参数，而不是使用所有的参数，他会分配给四个变量，然后你可以使用：script,first,second,和third，这可能看起来有些奇怪，但是“拆分”应该是描述这件事最好的词了。它好想在说：“无论argv中是什么，拆分它，然后把它按照顺序分配到左侧的这些变量上。”

然后我们会按照正常的方法把他们打印出来。

##等下，这个特点有另外一个功能

我称它为“特点”（这些你引入到你的程序中让Python程序可以做的更多的事情），但是没有人叫他们“特点”，我用这个名字是因为我需要不借助术语来告诉你他们是什么。在你继续之前，你应该知道他们的真正的名字"modules"（模块）。

从现在开始我们将称呼我们引入的“特点”为模块。我将会这么说“你想要引入sys模块”，其他程序员可能称之为“库”，我们就叫它“模块”好了

##你将会看到的

运行下面的程序，就像下面这样（记住一定要传入三个参数）

`$ python ex13.py first 2nd 3rd 
The script is called: ex13.py 
Your first variable is: first 
Your second variable is: 2nd 
Your third variable is: 3rd`

当你用不同的参数运行这段代码的时候，你会看到下面的东西

`$ python ex13.py stuff things that The script is called: ex13.py
Your first variable is: stuff Your second variable is: things Your third variable is: that
$
$ python ex13.py apple orange grapefruit The script is called: ex13.py
Your first variable is: apple
Your second variable is: orange
Your third variable is: grapefruit`

你可以用任何东西替换first,2nd和3rd

如果你没有正确的运行，你将会得到下面这样的结果：

`$ python ex13.py first 2nd Traceback (most recent call last):
File "ex13.py", line 3, in <module> script, first, second, third = argv
ValueError: need more than 3 values to unpack`

当你没有传递足够的参数的时候（在上面的例子里就是first 2nd），就会发生这样的事情。注意一下，当我运行的时候只给了first,2nd参数的时候，这会爆出一个错误“需要超过三个参数去拆分”，告诉你没有提供足够的参数

##进阶练习

##学生提问

- 为什么我运行的时候，得到了一个错误：need more than 1 value to unpack?<br />你要记住，注意细节是很重要的技能。如果你看看__你应该看到__章节，你就会看到我运行的时候在命令行中加了几个参数。你应该重复一下我是怎么运行的。
