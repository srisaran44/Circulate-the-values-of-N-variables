# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
### Step 6: 
## Program:
def circulate():
    arr = eval(input())   # reads list like ['a','b','c','d','e','f']
    k = int(input())
    
    n = len(arr)
    k = k % n
    
    # left circulation
    arr = arr[k:] + arr[:k]
    
    print("After circulating the values are:", arr)
## Output:
<img width="1291" height="800" alt="image" src="https://github.com/user-attachments/assets/55ff4b95-d572-4f10-ba0d-514726103c7f" />

## Result:
verified and executed succesfully
