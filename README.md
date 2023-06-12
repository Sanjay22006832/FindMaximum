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
Program to mark the maximum of marks using the list method sort
Developed by: M. Sanjay
RegisterNumber: 212222240090
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: M. Sanjay
RegisterNumber: 212222240090
def max_marks(marks):
    large=max(marks)
    return large
```
iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: M. Sanjay
RegisterNumber: 212222240090
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max= i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/Sanjay22006832/FindMaximum/assets/119830477/c6759ac3-9f35-4b74-852b-b8ac1544250d)

![image](https://github.com/Sanjay22006832/FindMaximum/assets/119830477/414ce7fa-8e64-4979-baf8-9d70fd2a2d2e)

![image](https://github.com/Sanjay22006832/FindMaximum/assets/119830477/e88d87e7-f87e-4fe1-bfed-fabcb5f991d4)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
