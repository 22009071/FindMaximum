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

Program to mark the maximum of marks using the list method sort

Developed by:kabilan T 

RegisterNumber: 22009071
```

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    



```

ii)	# To find the maximum marks using the list method max().

Program to find the maximum marks using the list method max().

Developed by: kabilan T

RegisterNumber: 22009071


```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    



```

iii) # To find the maximum marks without using builtin functions.

Program to the maximum marks without using builtin functions.

Developed by: kabilan T

RegisterNumber: 22009071

```
def max_marks(list1):
    temp=0
    for i in list1:
        if temp<i:
            temp=i
    return temp        
    



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![](maxp1![Uploading image.png…]()png)


![](maxp2"C:\Users\kabilan\Pictures\Screenshots\Screenshot_20230125_115708.png".png)

![](maxp3![image](https://user-images.githubusercontent.com/120206067/214652594-38036ba8-8508-498e-a229-ed69267a9249.png)
.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
