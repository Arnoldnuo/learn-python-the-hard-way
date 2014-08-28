##问问题

现在是时候来调整一下脚步了。我已经让你做了了很多输出，因此你应该已经了解了如何打印简单的东西，但是这些简单的东西是很无聊的。你现在想做的事情肯定是在你的程序中加入数据。这有些复杂，因为你必须学会做两件事，这才可能起作用，但是相信我，无论如何做一下。在一些练习中会起作用的。

大部分的软件都是做下面三件事：

1. 让某个人输入某些内容
2. 修改它
3. 打印出来它变成了什么样子

到目前为止，你一直在输出，但是你还不知道如何从一个人得到输入或者修改它。你可能已经知道了“输入”是什么意思，因此与其我们谈论这个，不如让我们做一些，然后看看你能不能明白。在几次练习中将会明白的。

`print "How old are you?", age = raw_input()
print "How tall are you?", height = raw_input()
print "How much do you weigh?", weight = raw_input()
print "So, you're %r old, %r tall and %r heavy." % ( age, height, weight)`

####注意
注意我们在每一行输出的结尾都加了一个“,”，这样的话输出不会把一行结束，然后跳到新行。

##你看的东西

`$ python ex11.py
How old are you? 38
How tall are you? 6'2"
How much do you weigh? 180lbs
So, you're '38' old, '6\'2"' tall and '180lbs' heavy.`

##进阶练习

1. 上网查一下python的`raw_input`是什么意思。

##学生提问
 
1. 当我打印字符串的时候，在前面有一个u，比如u'35'。<br />这是Python在告诉你这个字符串是unicode字符，使用%s这样打印出来的就是正常的了。
