#第七章：更多打印

现在我们将要做一些练习，你会打一些代码，然后让它运行起来。因为他们大多是相同的，所以我不会做任何解释。这一次的目的是为了加强你的能力。坐坐下面的练习，不要跳过！不要粘贴！

`print "Mary had a little lamb."print "Its fleece was white as %s." % 'snow' print "And everywhere that Mary went."print "." * 10 # what'd that do?end1 = "C" end2 = "h" end3 = "e" end4 = "e" end5 = "s" end6 = "e" end7 = "B" end8 = "u" end9 = "r" end10 = "g" end11 = "e" end12 = "r"# watch that comma at the end. try removing it to see what happensprint end1 + end2 + end3 + end4 + end5 + end6, print end7 + end8 + end9 + end10 + end11 + end12`
##你会看到的东西
`$ python ex7.pyMary had a little lamb.Its fleece was white as snow. And everywhere that Mary went. ..........Cheese Burger`
##进阶练习
对下面的几个练习，you will have the exact same extra credit.(此句不会翻译)
- 从现在开始，当你犯错以后，就把你的错误卸载一页纸上，记录下你做了什么错误。
- 记住每个人都会犯错。程序员在别人看来是那种每个人都认为不会犯错，非常完美的人，但是这只是假象。程序员也总是犯错。

##学生的问题

- **难道你不能不用逗号，然后把最后两行变成一行来打印？**<br />是的，当然你可以这样做，但是这将会让这一行超过80个字符，这在Python中是不好的风格。
