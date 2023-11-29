# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by:PAVITHRA.D
RegisterNumber: 23004871
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by:PAVITHRA.D 
RegisterNumber: 23004871
'''
def max_marks(marks):
    a=max(marks)
    return a

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: PAVITHRA.D
RegisterNumber: 23004871
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a        

```
## Output:
![m 1](https://github.com/PavithraD23004871/FindMaximum/assets/138955967/0dea0e07-a24e-4561-aee2-35fc34196006)
![m 2](https://github.com/PavithraD23004871/FindMaximum/assets/138955967/49e46c0c-10ed-4f0d-8235-02911c8d2e44)
![m 3](https://github.com/PavithraD23004871/FindMaximum/assets/138955967/697a1a12-f500-4e98-9559-5e40c0f8f23d)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
