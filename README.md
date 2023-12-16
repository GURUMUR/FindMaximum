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
Developed by: Gurumurthy S
RegisterNumber: 23013514
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Gurumurthy S
RegisterNumber: 23013514
'''
def max_marks(marks):
    # write your code here
    mark=max(marks)
    return mark


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Gurumurthy S
RegisterNumber: 23013514
'''
def max_marks(list1):
    max1=0
    for i in list1:
        if(i>max1):
            max1=i
    return max1


```
 
## Output:
1.To find the maximum of marks using the list method sort.
![Alt text](max_number(1).png)

2.To find the maximum marks using the list method max().
![Alt text](max_number(2).png)

3.To find the maximum marks without using builtin functions.
![Alt text](max_number(3).png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.