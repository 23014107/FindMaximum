# Find the maximum of a list of numbers
NAME:RAMYA.P
REG NO:212223240137
DEPARTMENT:AIML

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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark
```

## Output:
![image](https://github.com/23014107/FindMaximum/assets/151625620/34cb9a26-d43c-4865-a501-7d6f496aa302)
![image](https://github.com/23014107/FindMaximum/assets/151625620/a2e931e7-ba7e-4f65-8dc7-c43f2db0e337)
![image](https://github.com/23014107/FindMaximum/assets/151625620/29cae343-d9c4-4295-b01f-f56a3f40cc1c)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
