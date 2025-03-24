# DAY 1 - How to print, input and store

A simple but effective take on object oriented language, Python is an easy and powerful language that help seamlessly develop real world applications leveraging  its elegant syntax, dynamic typing and interpreted nature.  

## Print
As custom, before advancing, we need to do the inaguatory ritual of priniting hello world! :D 
```
print("Hello World")
```

>**Note** : Python doesn't use semicolon for ending statements, rather is very strict with the indentation. 


## Input
Taking iputs in python means:
```
input("What is your name?")
```
The input statement holds the value entered through console, so a clever way to dynamically greet users based on their names would be:

```
print("Hello "+ input("What is your name?"))
```
## Variables
But indeed, the previous method makes it impractical for lengthy inputs. 

Here's another scenario- Imagine if you want your computer to remember data while executing code? 

So why not **store** them?
```
name= str(input("What is your name?"))
age= str(input("How old are you?"))

print("Hi" + name)
print("Hi "+name+ "! You are "+age+ "years old")
```
>**Note** : The input is by default of type Int. In order to concatenate the variable in a string after storing the input in the print statement, it is essential to cast it to string using str().

#### Rules
- Varibales cannot be reseved keywords.
- Variables can only start with character or underscore.
- They can only contain alpha-numeric characters and no special characters except for underscore.
- They are case-sensitive. 
