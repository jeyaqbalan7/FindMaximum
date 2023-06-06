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
Developed by: Jeyabalan
RegisterNumber: 212222240040
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Jeyabalan
RegisterNumber: 212222240040
'''
def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Jeyabalan
RegisterNumber: 212222240040
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

``` 
## Output:
1.) To find the maximum of marks using the list method sort.
![image](https://github.com/jeyaqbalan7/FindMaximum/assets/119393851/cae71eff-734b-4f48-a478-8b16f8057819)

2.) To find the maximum marks using the list method max().
![image](https://github.com/jeyaqbalan7/FindMaximum/assets/119393851/b47d9918-f9f6-4a74-9558-1c7220f95298)

3.) To find the maximum marks without using builtin functions.
![image](https://github.com/jeyaqbalan7/FindMaximum/assets/119393851/8a142f50-434b-4657-a966-0fed768e5592)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
