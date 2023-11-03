# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using the concatenation operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Jerowin Geo J A
#RegisterNumber:23013644
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![image](https://github.com/JerowinGeo/Circulate-the-values-of-N-variables/assets/147139744/14f15215-4d98-4fbd-91fa-681613599e08)


## Result:
Thus, the python program for "Circulate the values of n variables" has been executed successfully.
