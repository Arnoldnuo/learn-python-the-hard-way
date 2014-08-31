#对人们加提示

当你输入`raw_input()`的时候，你打了(和)两个括号字符，你应该感觉很熟悉，当你用他们来格式化额外的变量的时候，比如在"%s %s"%(x,y)中。对于`raw_input`你可能也会输入一些提示来展示给人们，这样人们知道要输入什么。把你要输入的提示放在()里面，看起来就像下面这样:

`y = raw_input("Name? ")`

这个提示使用"Names?"来让人们输入变量y，这就是你问人们一个问题，然后让他们来回答。

这代表着我们可以完全通过`raw_input`重写我们之前的练习，然后来做所有的提示

`age = raw_input("How old are you? ")
height = raw_input("How tall are you? ") weight = raw_input("How much do you weigh? ")
print "So, you're %r old, %r tall and %r heavy." % ( age, height, weight)`

##你看到的内容

`$ python ex12.py
How old are you? 38
How tall are you? 6'2"
How much do you weigh? 180lbs
So, you're '38' old, '6\'2"' tall and '180lbs' heavy.`

##进阶练习

1. 在Terminal中输入`pydoc raw_input`，读一下它的内容是什么。如果你使用的是windows，那么使用`python -m pydoc raw_input`。
2. 输入q来退出pydoc
3. 在线查找一下pydoc是干嘛用的
4. 使用pydoc来读一读open, file, os和sys，如果你不懂这些内容，就浏览一下，然后记下有趣的东西。

##学生提问
