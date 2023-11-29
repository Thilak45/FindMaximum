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
'''Program to mark the maximum of marks using the list method sort
Developed by: v.tilak
RegisterNumber: 23009564'''
def max_marks(marks):
    marks.sort()
    max_mark = marks[-1]
    return max_mark
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: v.tilak
RegisterNumber: 23009564
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max = i
    return max
```
## Sample Input and Output

![image](https://github.com/Thilak45/FindMaximum/assets/138849161/dd86519b-59c5-44d0-aad9-8e605f285aa0)

![image](https://github.com/Thilak45/FindMaximum/assets/138849161/a096e927-9306-4cf4-93a9-b42122b2ec18)

![image](https://github.com/Thilak45/FindMaximum/assets/138849161/93f5b1dd-8e49-46ef-ae91-79c687e23bd5)

## Output:

![image](https://github.com/Thilak45/FindMaximum/assets/138849161/b0ef7007-63bb-4dfb-af86-0486c3a791ad)

![image](https://github.com/Thilak45/FindMaximum/assets/138849161/5230365e-cb21-4ec7-9b50-5e867adf5892)

![image](https://github.com/Thilak45/FindMaximum/assets/138849161/1481e3cd-5ee1-4d41-8a01-afd0895e5d9e)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
