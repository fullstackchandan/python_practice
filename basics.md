#function in python

def myFun(name):
    print(name)
    
myFun('chandan')

#function for evenOdd

def evenOdd(num):
    if num % 2 == 0:
        print(num,"is even no")
    else:
        print(num,"is odd no")
    
evenOdd(55225479)

# for loop as list iterator
def list_iterator(list_name):
    for i in a:
        print(i)


a = []
a.append(5)
a.append(67)
list_iterator(a)
    
# stack

list = []

def push(list_name):
    list_name.append(45)
    list_name.append(34)
    
def delete(list_name):
    print("item deleted is",list_name.pop())

def display(list_name):
    for item in list_name:
        print(item)
    
def top(list_name):
    print("Top item is ",list_name[len(list_name)-1])
    
push(list)
display(list)
top(list)
delete(list)

#OOPS in python
class Bike:
    name = ""
    gear = 0
    
    def features():
        main = "track ready"
        wheels = "bridgestone"

# create object of class
bike1 = Bike()
bike1.name = "rajdoot"
bike1.gear = 4

print(f"Name: {bike1.name}, Gears: {bike1.gear}")
print(f"Bike is: {bike1.features().main} and having all weather {bike1.features().wheels} installed")
# error correction required
