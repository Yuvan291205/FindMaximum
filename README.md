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
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    # write your code here
    maximum = max(marks)
    return maximum


```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```
## Output:
![output](./img/max_marks1.jpg) 
![Screenshot 2023-12-21 151156](https://github.com/Yuvan291205/FindMaximum/assets/138849170/375dd847-9eef-4919-bd7d-00ef843108cf)
![Screenshot 2023-12-21 151206](https://github.com/Yuvan291205/FindMaximum/assets/138849170/68656ad9-f55a-49f1-afbb-47b59c8a90ed)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
