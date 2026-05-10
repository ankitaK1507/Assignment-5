# Assignment-5
# Python program to calculate the length of a string

string = input("ankita: ")

length = len(string)

print("Length of the string is:", length)

Out put :
Length of the string is: 6


# Python program to make a string 
# from first 2 and last 2 characters

string = input("Python: ")

if len(string) < 2:
    print("Empty string")
else:
    result = string[:2] + string[-2:]
    print("New string:", result) 

Out put : 
New string: Pyon

 
# Python program to concatenate two strings

string1 = input("Hello: ")
string2 = input("World: ")

result = string1 + string2

print("Concatenated string is:", result)

Output : 
Concatenated string is: HelloWorld
