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
#Program to mark the maximum of marks using the list method sort
#Developed by: Tejaswini.G
#RegisterNumber:22003358 

def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Developed by:Yogeshvar.M
#RegisterNumber: 22003358

def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to the maximum marks without using builtin functions.
#Developed by: Yogeshvar.M
#RegisterNumber: 22003358 

def max_marks(list1):
    for i in list1:
        if i>=95:
            return i
        else:
            pass
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
<img width="437" alt="image" src="https://user-images.githubusercontent.com/121222763/214497349-309d0bb3-1d63-4f2f-bd49-ac2a15ab9aa7.png">
<img width="443" alt="image" src="https://user-images.githubusercontent.com/121222763/214497400-e1d3b0cc-3575-430a-b3a5-07c5078bed57.png">
<img width="443" alt="image" src="https://user-images.githubusercontent.com/121222763/214497423-8a836ada-c4d1-4ca7-af40-0d84a40cdfe9.png">

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
