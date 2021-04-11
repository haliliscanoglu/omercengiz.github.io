# omercengiz.github.io
Omer Cengiz
HW-01
mylist=[1,2,3,4,5,6,7,8,9,10]
>>> i=j=0
>>> for j in range(5):
	temp=[i]
	temp=mylist[i]
	mylist.pop(i)
	mylist.append(temp)
	print(mylist)
  
  HW-02
  sy = input('İput single digit integer number as an n:\n')
try:
    if int(sy)>=0:
        print("Even numbers:")
        for i in range(int(sy)):
            if i % 2 == 0:
                print(i)       
except:
        print(i)
        
HW-03
username = input("Please enter your username : ")
password = input("Please enter your password : ")
print (username,"\nYou are now logged in successfully")

command = input("Please type a command :")
if command == "log off":
    print ("You have now been logged off again",username)
    username == ""
    password == ""

username = input("Please enter your username : ")
password = input("Please enter your password : ")
while (username !="username" and password !="password"):
    print ("Sorry username and password incorrect please re-enter for validation")
    username = input("Please enter your username : ")
    password = input("Please enter your password : ")
else:
    print (username,"You are now logged in successfully")
