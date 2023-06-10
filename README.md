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
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

iii) # To find the maximum marks without using builtin functions.
```Python
'''
def max_marks(list1):
    list1.sort()
    return list1[-1]

```
## Output:
![image](https://github.com/Meetha22003992/FindMaximum/assets/119401038/6db30e4c-a7ff-4f55-80ff-309a183b57c0)

![image](https://github.com/Meetha22003992/FindMaximum/assets/119401038/ef1c6745-7d08-4d31-9c43-25442dea7a63)

![image](https://github.com/Meetha22003992/FindMaximum/assets/119401038/87999679-be8c-4357-b2ef-e7c219d686f9)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
