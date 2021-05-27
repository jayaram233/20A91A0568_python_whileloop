# 20A91A0568_python_whileloop
While loop
a=1
while (a<=10):
	print(a)
	a=a+1
	
print ("after while loop the value of i is {}".format(a))
print ("after while loop the value of i is %d" %(a))


Output:
1
2
3
4
5
6
7 
9
10
After while loop the value of i is 11
After while loop the value of i is 11


#user inputs 

a=int(input("enter the value :"))
b=int(input("enter the value:"))
while (a<=10):
	print(a)
	a=a+b
	
print ("after while loop the value of a is {}".format(a))
print ("after while loop the value of a is %d" %(a))

Output:
enter the value: 1
enter the value: 2
1
3
5
7
9
After the while loop the value of a is 11
After the while loop the value of a is 11
