This library will help you to generate ramdom email ids on the basis of numbers you provide as arguments to the script.
Syntax:
  python ./reidg/__init__.py number emailProvider
For example: 
Input: python ./reidg/__init__.py 898 yopmail.com
Output: 
  Number of emails to generate: 3
  wmNQxNIGyopmail.com
  FnkYCKdVYyopmail.com
  dYEcEygoyopmail.com
  
So how to import and use in your python script?
Method 1: 
test.py
	import reidg
	reidg.main()
  
> python test.py 345 gmail.com
Number of emails to generate: 3
yMj@gmail.com
gYgh@gmail.com
APBvz@gmail.com

Method 2:
test.py
	import reidg
	list_of_num = reidg.convert_to_list(99999)
	email_provider = "yopmail.com"
	reidg.random_char(list_of_num, email_provider)

> python test.py
PNGAaVYFu@yopmail.com
wSJvEhWTa@yopmail.com
dYEyOSylO@yopmail.com
XJhEmvwXW@yopmail.com
NkHKqsNCp@yopmail.com
