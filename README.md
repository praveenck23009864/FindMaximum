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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: praveen ck
RegisterNumber: 23009864
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by: praveeen ck
RegisterNumber: 23009864
'''
def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: praveen ck
RegisterNumber: 23009864
'''
def max_marks(list1):
    maximum=list1[0]
    for i in list1:
        if i>maximum:
            maximum=i
    return maximum
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
# To find the maximum of marks using the list method sort.
![image](https://github.com/praveenck23009864/FindMaximum/assets/141472050/7885f7de-52a7-4ab8-aa95-ab65f5250c6b)
# To find the maximum marks using the list method max().
![image](https://github.com/praveenck23009864/FindMaximum/assets/141472050/00fa9bbe-190e-4736-8db7-0d846de1b82e)
# To find the maximum marks without using builtin functions.
![image](https://github.com/praveenck23009864/FindMaximum/assets/141472050/51290862-47fc-419e-881d-c0b92c38ea95)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
