# sashi
#Swapping of elements
a=1
b=2
a,b=b,a
print(a,b)
///
a=1
b=2
temp=a
a=b
b=temp
print("a:",a)
print("b:",b)
///
# temp variale swapping
a=1
b=2
temp=a
a=b
b=temp
print("a:",a)
print("b:",b)
a=-190
b=288
temp=a
a=b
b=temp
print("a:",a)
print("b:",b)
///
# Swappig by using arithmetic operators
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a*b
b=a/b
a=a/b
print("after swapping")
print("a:",a)
print("b:",b)
///
#Swappig By using Truth Tables by covertiig decimal to binary and follow the implementation as
usual like before swapping examples
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a^b
b=a^b
a=a^b
print("after swapping")
print("a:",a)
print("b:",b)
///
#String pushing
fruits=['apple','mango','cherry']
print(fruits)#print string
print(fruits[1])#print of certain fruit name using index
print(fruits[0])
print(fruits[2])
fruits[2]='banana'#editig name of fruit in a string
print(fruits)#print string after editing
print(fruits[2])
print(fruits[-3])
///
#Operations using list
nums=[0,1,2,3,4,5,6,7,8,9]
print(len(nums))
print(nums[1],nums[2],nums[3])
print(nums[0:11])
print(nums[3:5])#slicing(single colon)
print(nums[::3])#skippig of certai index position (double colon)
print(nums[::-1])
print(nums[::-3])
print(6 in nums) #membership operator only in boolean expression (true/false)
print(11 in nums)
///
#string sort
fruits=['apple','mango','cherry']
fruits.sort() #sorting wrt ascii values
print(fruits)
fruits.reverse() #printng by decrement order
print(fruits)
///
#Nested list operations
nestnum=[[1,2], [3,4], [5,6]]
print(nestnum[1]) #index of num
print(nestnum[2][0]) #index of index of num
print(nestnum[1][1]) # here it is printing 1st index position of num and i that printing 1st index postion of[3,4] its is known as nested list..
nestnum[2][1]=99
print(nestnum)
nestnum[2]=100
print(nestnum)
l2=[[1,2],[3,4]]
l2.append([11,22])
print(l2)
///
