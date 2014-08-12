#第五章：更多变量和打印

现在我们输入更多地变量，然后把他们打印出来。这一次我们使用一个叫做“字符串格式化”地东东。每一次你在一些文字两侧加上"（双引号）的时候，你就是制造了一个字符串。字符串是你的程序会展示给人类看的东西。你把他们打印出来，储存进文件，发送给web服务器，或者各种东西。

字符串是相当便捷的，因此在这章的练习中你将会学习如何创造包含变量的字符串。你通过使用特定的格式语句把变量插入到字符串中，然后把变量加上一个特殊的语法放到最后，这就是告诉了python，“这是一个格式化字符串，把这些变量放到那里”。  

想平常一样，如果你不明白，就把下面的东西输入文件中，然后让他们一样。

`
my_name = 'Zed A. Shaw' 
my_age = 35 # not a lie 
my_height = 74 # inches 
my_weight = 180 # lbs 
my_eyes = 'Blue' 
my_teeth = 'White' 
my_hair = 'Brown'print "Let's talk about %s." % my_nameprint "He's %d inches tall." % my_heightprint "He's %d pounds heavy." % my_weightprint "Actually that's not too heavy."
print "He's got %s eyes and %s hair." % (my_eyes, my_hair)
print "His teeth are usually %s depending on the coffee." % my_teeth# this line is tricky, try to get it exactly rightprint "If I add %d, %d, and %d I get %d." % (my_age, my_height, my_weight, my_age + my_height + my_weight)`
####警告
记住，如果你使用的是非ASCII字符，而且报错了，那么要把 # -- coding: utf-8 -- 放到文章顶部。
###你会看到的东西
`$ python ex5.py
Let's talk about Zed A. Shaw.He's 74 inches tall.He's 180 pounds heavy.Actually that's not too heavy.He's got Blue eyes and Brown hair.His teeth are usually White depending on the coffee. If I add 35, 74, and 180 I get 289.`
###进阶练习
1. 多试几个格式化字符，%r是一个非常有用的字符，它的意思是“无论是什么都打印出来”。
2. 在线搜索所有的python格式化字符。

###学生提问
