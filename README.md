# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Store the values for rotation in a variable
### Step 2: 
Get the value from the user for the number of rotation

### Step 3: 
Execute the print statement
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the values
### Step 6:
End the program 
## Program:
```
#Program to circulate N values.
#Developed by: Shavedha
#RegisterNumber:21500429
def circulate():
    a=[10,20,30,40,50,60]
    b=int(input())
    result=a[b:]+a[:b]
    print("After circulating the values are:",result)
```

## Output:
![OUTPUT](./exo2.png)

## Result:
Thus the circulating of the values are successfully executed 
