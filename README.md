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
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num


```



## Output:
i)To find the maximum of marks using the list method sort.
![Screenshot 2024-04-06 084302](https://github.com/KAMALESHNITHYA/FindMaximum/assets/145743119/e15efd7e-c45c-4cb7-8cfb-2c2bdde9b879)
ii)To find the maximum marks using the list method max().
![Screenshot 2024-04-06 084451](https://github.com/KAMALESHNITHYA/FindMaximum/assets/145743119/4bea4956-2c5e-4a5f-b766-e6d20d6901cc)
iii)To find the maximum marks without using builtin functions.
![Screenshot 2024-04-06 084529](https://github.com/KAMALESHNITHYA/FindMaximum/assets/145743119/f3907997-7159-4db6-b97e-ccce9a22e109)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
