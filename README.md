# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the interchanged values
### Step 6: 
End the program
## Program:
```
#Developed By : Krishna Prasad.S
#Register No : 212223230108
```
```

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2024-05-08 042248](https://github.com/KrishnaPrasad148/Circulate-the-values-of-N-variables/assets/147332763/380ead3e-af29-4387-990c-10c36874bb78)

![Screenshot 2024-05-08 042305](https://github.com/KrishnaPrasad148/Circulate-the-values-of-N-variables/assets/147332763/d65a22ce-9342-48f1-98d9-1cc30af82067)


## Result:
The program to circulate the values of n variables is executed succesfully
