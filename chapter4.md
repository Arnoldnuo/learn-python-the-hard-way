#第四章：变量和命名

现在你可以使用`print`来打印东西，而且你也可以做数学运算了。下一步就是学习变量。在编程中，变量只是某些东西的名字，这样你可以使用他们的名字而不是你写的其他东西。程序员使用变量名让他们的代码读起来更像英语，而且因为他们记忆力很差。如果他们不在他们的软件中使用合适的名字，当他们想读自己的代码的时候将会什么也不知道。  
如果你在这一章遇到了困难，记住你曾经学过的如何找到区别和关注细节的能力：  
1. 对每一行写下注释，用英语给你自己解释这一行做了什么。
2. 重头读一下你的.py文件
3. 大声读出你的.py文件，甚至每一个字符都要读出来。

`cars = 100space_in_a_car = 4.0drivers = 30passengers = 90cars_not_driven = cars - driverscars_driven = driverscarpool_capacity = cars_driven * space_in_a_car 
average_passengers_per_car = passengers / cars_driven`
`print "There are", cars, "cars available."print "There are only", drivers, "drivers available."print "There will be", cars_not_driven, "empty cars today."print "We can transport", carpool_capacity, "people today."print "We have", passengers, "to carpool today."print "We need to put about", average_passengers_per_car, "in each car."`


####注意
在`_in_a_car`中的`_`符号叫做下划线，如果你不知道怎么打这个符号，查一查。我们用这个字符来在变量名中加一个假象的空格。

###你应该看到的东西
`$ python ex4.pyThere are 100 cars available.There are only 30 drivers available. There will be 70 empty cars today. 
We can transport 120.0 people today. 
We have 90 to carpool today.We need to put about 3 in each car.`

###进阶练习
当我第一次写这个程序的时候，我犯了一个错误，然后python告诉了我下面的东西:

`Traceback (most recent call last):
    File "ex4.py", line 8, in <module>		average_passengers_per_car = car_pool_capacity / passenger 
	NameError: name 'car_pool_capacity' is not defined`

用你自己的话解释一下这个错误，确定你使用了行好然后解释了为什么。  
下面是其他的练习：
1. 我使用了4.0作为space_in_a_car的值，这是必须的吗？如果我使用4会造成什么结果？
2. 记住4.0是一个浮点数，查一下这表示什么。
3. 确定你知道=叫什么（等于），然后它是给东西命名的。
4. 记住_是一个下划线符号

###学生提问