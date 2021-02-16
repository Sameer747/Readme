# Readm
## INTRODUCTION
After unzipping  the zip file open java file I hope you have Netbeans installed just click on the green button to run the program if you dont search the internet to download netbeans or any other IDE.
### TASK-01
The task-1 is about tree traversal in which we have to implement traversal of trees
#### Output
Following should be the output.
####
PRE-ORDER:
a 
b 
c 
e 
f 
d 
g 
####
POST-ORDER:
f 
e 
c 
d 
b 
g 
a 
####
IN-ORDER:
e 
f 
c 
b 
d 
a 
g 
### TASK-02
The task-2 is about to implement 5 design pattern following are the design pattern I implemented
1)Singleton
2)Factory
3)Prototype
4)Decorator
5)Observer
#### Singleton
In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system.I have followed an example of Configuration Manager that has to load the default properties for the system and also It should support the updates for the properties and make the updates available.
#### Output
Following should be the output.
####
instance password:123456
####
instance2 password:123456
#### Factory
In class-based programming, the factory method pattern is a creational pattern that uses factory methods to deal with the problem of creating objects without having to specify the exact class of the object that will be created. This is done by creating objects by calling a factory method—either specified in an interface and implemented by child classes, or implemented in a base class and optionally overridden by derived classes—rather than by calling a constructor.I have followed an example  example, we will consider the use case of the Logistics Industry. We will build a Shipping company, which ships goods via all modes of transport.
#### Output
Following should be the output.
####
Handling Land Logistics
####
Loaded Truck with freight
####
Truck has hit the road
####
Handling Sea Logistics
####
Loaded ship with freight
####
Ship has set Sail
#### Prototype
The prototype pattern is a creational design pattern. Prototype patterns is required, when object creation is time consuming, and costly operation, so we create object with existing object itself. One of the best available way to create object from existing objects are clone() method. Clone is the simplest approach to implement prototype pattern. However, it is your call to decide how to copy existing object based on your business model.I have followed an example of vehicle system that clones and avoid multiple object creation of same instance so it copy the object to new object & then modified.
#### Output
####
[Honda amaze, Audi A4, Hyundai Tucson, Suzuki Baleno, Toyota Mark X]
####
[Honda amaze, Audi A4, Hyundai Tucson, Suzuki Baleno, Toyota Mark X, Honda new Amaze]
####
[Honda amaze, Hyundai Tucson, Suzuki Baleno, Toyota Mark X, Honda new Amaze]
####
[Honda amaze, Audi A4, Hyundai Tucson, Suzuki Baleno, Toyota Mark X]
#### Decorator
Decorator pattern allows a user to add new functionality to an existing object without altering its structure. This type of design pattern comes under structural pattern as this pattern acts as a wrapper to existing class.I have followed an example of simple dress customization websites that adds the features of the dress at runtime.
#### Output
####
Basic Dress Features
####
Adding Sporty Dress Features
####
Basic Dress Features
####
Adding Fancy Dress Features
####
Basic Dress Features
####
Adding Casual Dress Features
####
Basic Dress Features
####
Adding Fancy Dress Features
####
Adding Sporty Dress Features
####
Basic Dress Features
####
Adding Fancy Dress Features
####
Adding Casual Dress Features
#### Observer
The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.I have followed an example of Loan on which interest rate is subject to change and when it changes, Loan notifies to Newspaper or Internet media to display a new loan interest rate.
#### Output
####
Notifying Observers on change in Loan interest rate
####
Newspaper: Interest Rate updated, new Rate is: 3.5
####
Notifying Observers on change in Loan interest rate
####
Internet: Interest Rate updated, new Rate is: 3.5









