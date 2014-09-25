# 提示和传参

让我们做一个一起使用argv和raw_input，然后询问用户某些明确内容的练习。你需要这些来进行下一章中读写文件的练习。在这个练习中，我们将有些许不同地使用raw_input，然后打印出一个简单地>富豪，这像是一个文字冒险游戏。

`from sys import argv script, user_name = argv
prompt = '> '
print "Hi %s, I'm the %s script." % (user_name, script) print "I'd like to ask you a few questions."
print "Do you like me %s?" % user_name
likes = raw_input(prompt)
print "Where do you live %s?" % user_name lives = raw_input(prompt)
print "What kind of computer do you have?" computer = raw_input(prompt)
print """
Alright, so you said %r about liking me. You live in %r. Not sure where that is. And you have a %r computer. Nice.
""" % (likes, lives, computer)`

注意一下，我们使用了一个prompt变量，然后设置成我们想要地>符号，然后我们把它传递给raw_input而不是一次又一次地输入。现在如果我们想做一些其他地提示，我们可以在一个位置修改它，然后重新运行这个脚本

十分方便。

##你看到的

当我们运行这个脚本的时候，记住你已经给了这个脚本的名字传递给了argv变量

`$ python ex14.py zed
Hi zed, I'm the ex14.py script.
I'd like to ask you a few questions. Do you like me zed?
> Yes
Where do you live zed?
> San Francisco
What kind of computer do you have? > Tandy 1000
Alright, so you said 'Yes' about liking me.
You live in 'San Francisco'. Not sure where that is. And you have a 'Tandy 1000' computer. Nice.`

##进阶练习

1. 确认你明白如何使用"""连接一个多行字符串，然后使用%来格式化输出。

##学生提问


