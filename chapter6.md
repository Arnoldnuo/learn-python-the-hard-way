#第六章：字符串和文字

当你已经写了字符串后，你仍然不知道他们是干什么的。在这一章中，我们将创建更多变量和更复杂的字符串，这样你就可以看到他们是用来干什么的。首先解释一下字符串。

字符串通常是你想展示给某个人或者从你正在写的程序中输出的一些文本。当你在一些文本两侧加上单引号或者双引号的时候，python知道你想让这些东西成为字符串。你已经见过很多次了，当你把你想放到"或'之间的文本放到`print`之后的时候，python就把它打印出来了。

你已经发现了，字符串可能含有格式化字符。你只是把格式化变量放到了字符之中，然后使用一个%符号跟在变量后面。有一个坑是如果你想把多种格式放到你的字符串中，你需要把他们放到括号里面，然后使用逗号分割。看起来就好像你告诉我去商店买一些东西，然后你说“我想要牛奶，鸡蛋，面包和汤”，就像是程序员在说"(牛奶,鸡蛋,面包,汤)"

我们现在输入一些字符串，变量名，和格式符，然后打印出来。你也会练习使用变量名。程序员喜欢节省他们的时间，这样导致的后果就是你使用那些令人抓狂的含糊不清的变量名，因此你应该从最开始就使用可读性好的，然后把他们写出来。

`x = "There are %d types of people." % 10binary = "binary"do_not = "don't"y = "Those who know %s and those who %s." % (binary, do_not)print x 
print yprint "I said: %r." % xprint "I also said: '%s'." % yhilarious = Falsejoke_evaluation = "Isn't that joke so funny?! %r"print joke_evaluation % hilarious 
w = "This is the left side of..."e = "a string with a right side." 
print w + e`

###你看到的东西
`$ python ex6.pyThere are 10 types of people.Those who know binary and those who don't.I said: 'There are 10 types of people.'.I also said: 'Those who know binary and those who don't.'. 
Isn't that joke so funny?! FalseThis is the left side of...a string with a right side.`
###进阶练习
###学生提问

- %r和%s有什么区别？  
	使用%r来调试，因为它会展示变量中所有的数据，但是使用其他的来给用户展示。