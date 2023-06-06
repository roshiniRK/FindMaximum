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
Developed by: ROSHINI RK
RegisterNumber: 212222230123
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
Developed by:ROSHINI RK 
RegisterNumber: 212222230123
'''
def max_marks(marks):
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: ROSHINI RK
RegisterNumber: 212222230123
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
## Output:
![image](https://github.com/roshiniRK/FindMaximum/assets/118956165/59f6e64f-7195-46b9-b3b5-6e4b7fbb4203)


![image](https://github.com/roshiniRK/FindMaximum/assets/118956165/55610457-850a-401b-87b1-1c975ce8c7f7)


![image](https://github.com/roshiniRK/FindMaximum/assets/118956165/b53f6bad-cc7f-459a-ba37-351db94ff118)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
