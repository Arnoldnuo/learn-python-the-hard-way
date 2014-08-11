#第三章：数字和数学计算

每一种编程语言都有几种关于数字和数学计算的方法。不要担心，程序员经常说谎说自己是数学天才，其实他们不是。如果他们是数学天才，他们应该是去研究数学，而不是写广告和社交游戏来偷人们的钱。

这个练习有很多数学符号，让我们给他们命名，然后你可以知道他们应该叫什么。在你打这个文字的时候，说它的名字。当你感觉念出来的时候很无聊，那么你可以停止说。下面就是名字。

- \+ 加
- \- 减
- / 除
- \* 乘
- % 百分号
-  < 小于
-  \> 大于
-  <= 小于或等于
-  \>= 大于或等于

注意到了没有，我没有写操作的具体行为。在你在这章的练习中写了这些代码以后，回来看一看每一个运算符都是做了什么，然后完成这个表格。比如，＋做加法。

`￼print "I will now count my chickens:" 
print "Hens", 25 + 30 / 6print "Roosters", 100 - 25 * 3 % 4 
print "Now I will count the eggs:" 
print 3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6 
print "Is it true that 3 + 2 < 5 - 7?" 
print 3 + 2 < 5 - 7print "What is 3 + 2?", 3 + 2 
print "What is 5 - 7?", 5 - 7print "Oh, that's why it's False." 
print "How about some more."print "Is it greater?", 5 > -2print "Is it greater or equal?", 5 >= -2 
print "Is it less or equal?", 5 <= -2`

###你应该看到的输出
`$ python ex3.pyI will now count my chickens: 
Hens 30Roosters 97Now I will count the eggs:7Is it true that 3 + 2 < 5 - 7? FalseWhat is 3 + 2? 5What is 5 - 7? -2Oh, that's why it's False.How about some more.Is it greater? TrueIs it greater or equal? True Is it less or equal? False`
###进阶练习
1. 对上面的每一行都用#写一行注释来解释每一行多做了什么
2. 还记得在最开始的时候你在第0章做的练习吗？启动python，然后使用上面的字符和你所知道的东西，把python当作计算器来使用。
3. 有没有看到这些计算结果好像有“错误”，没有小数，只有分数。研究一下“浮点数”是什么东西。
4. 使用浮点数重新写ex3.py,让运算结果更加精确。（提示：20.0就是一个浮点数）。

###学生提问
