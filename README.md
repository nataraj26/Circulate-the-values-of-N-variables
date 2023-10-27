# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function.
### Step 2: 
Get the variables from user to enter inside the list.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.
### Step 5: 
After rotating the variables, store the rotated variables in a seperate list.
### Step 6: 
At last, print the list of rotated variables.
## Program:
~~~
#Program to circulate N values.
#Developed by: NATARAJ KUMARAN S
#RegisterNumber: 23003973
def circulate():
    lst=eval(input())
    n=int(input())
    result=lst[n:]+lst[:n]
    print("After circulating the values are:",result)
~~~
## Output:
![image](https://github.com/nataraj26/Circulate-the-values-of-N-variables/assets/147514615/15f9c987-42a2-4265-ad95-018d1a3e9c3d)

## Result:
Thus the python program to circulate the n variable using function concept is successfully executed.
