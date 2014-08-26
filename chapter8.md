#打印，打印

`formatter = "%r %r %r %r"
formatter = "%r %r %r %r"
print formatter % (1, 2, 3, 4)
print formatter % ("one", "two", "three", "four")
print formatter % (True, False, False, True)
print formatter % (formatter, formatter, formatter, formatter) print formatter % (
"I had this thing.",
"That you could type up right.", "But it didn't sing.",
"So I said goodnight."
)`

##你应该看到的东西

`$python ex8.py
1234
'one' 'two' 'three' 'four'
True False False True
'%r %r %r %r' '%r %r %r %r' '%r %r %r %r' '%r %r %r %r'
'I had this thing.' 'That you could type up right.' "But it didn't sing." 'So I said goodnight.'`

##进阶练习

1. 有没有注意到最后一行的输出既使用了单引号也使用了双引号来表示字符串片段。你认为为什么会是那样子的呢？

##学生提问

- **我尝试在字符串中加入中文或者其他非ASCII字符**，但是%r打印出来的是很奇怪的字符<br/>使用%s来打印，它会起作用的。
- **为什么%r有时候会把我写的双引号当单引号打印出来？**<br/>python会用自己最有效率的方法打印字符串，并不会完全复制你写的样子。因为%r是用来调试的，所以没有必要做的一样啊。
