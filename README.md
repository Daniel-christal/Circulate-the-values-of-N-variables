# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
start the program

### Step 2:
give the variables inside the function

### Step 3: 
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
after slicing your values grt circulated
### Step 6: 
we can change the values to be circulated from an element to element 
## Program:
def circulate(): 
   l=eval(input())
   n=int(input())
   l=l[n: ]+l[ :n]
   print("After circulating the values are:",l)
## Output:
![Alt text](image.png)
## Result:
circulate n variables executed successfully
