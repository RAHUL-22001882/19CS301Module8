# 19CS301 Module8
EXPTNO.8a Program to find Find the simple interest

### Aim: 
To Write a python program to find the time taken to cross an electric pole? [Distance = speed*time]

### Algorithm:

STEP 1: Start.

STEP 2:Assign the value 75 to the variable dis.

STEP 3:Multiply 54 by (5 / 18) and store the result in speed.

STEP 4: time = dis / speed

STEP 5: Print the value of time.

STEP 6: Stop.

### Program:
```
dis=75
speed=54*(5/18)
print(dis/speed)
```
### Output:
![Screenshot 2025-06-02 135016](https://github.com/user-attachments/assets/ebbd6d4e-a330-447e-bd1d-749448d4bf49)


### Result: Thus, the given program is implemented and executed successfully .

EXPTNo.8b program to print the numbers in reverse order.

### Aim: 
To Write a python program to print the numbers in reverse order

### Algorithm:

STEP 1: Start.

STEP 2: Get the input of a from user.

STEP 3: Using while loop .

STEP 4: get the unit digit.

STEP 5:print modulo 10

STEP 6: Stop.

### Program:
```
n=int(input())
while(n>0):
    print(n%10,end="")
    n=n//10

```
### Output:
![Screenshot 2025-06-02 135150](https://github.com/user-attachments/assets/8323515a-953b-4c40-a975-4fe335868986)


### Result: Thus, the given program is implemented and executed successfully .
 

EXPT NO:8C read in the value of n followed by n lines of commands where each command will be of the 7 types


### Aim: 
To Initialize your list and read in the value of n followed by n lines of commands where each command will be of the 7 types. Iterate through each command in order and perform the corresponding operation on your list.

### Algorithm:
Start the program.

Input an integer N (the number of commands to be executed).

Initialize an empty list l.

Repeat the following steps N times:

Read a line of input and split it into a list s.

Based on the first element of s (i.e., the command), perform the corresponding operation:

If s[0] is 'insert': insert int(s[2]) at index int(s[1]) in list l.

If s[0] is 'remove': remove the first occurrence of int(s[1]) from list l.

If s[0] is 'append': add int(s[1]) to the end of list l.

If s[0] is 'pop': remove the last element of the list l.

If s[0] is 'sort': sort the list in ascending order.

If s[0] is 'reverse': reverse the order of elements in the list.

If s[0] is 'print': display the current state of the list l.

End the program.

### Program:
```
N=int(input())
l=[]
for i in range(N):
    s=input().split()
    if s[0]=='insert':
        l.insert(int(s[1]),int(s[2]))
    elif s[0]=='remove':
        l.remove(int(s[1]))
    elif s[0]=='append':
        l.append(int(s[1]))
    elif s[0]=='pop':
        l.pop()
    elif s[0]=='sort':
        l.sort()
    elif s[0]=='reverse':
        l.reverse()
    elif s[0]=='print':
        print(l)
```
### Output:
 
![Screenshot 2025-06-02 135325](https://github.com/user-attachments/assets/23b79f02-d03e-44bf-af95-0ee328d6ffc9)

### Result: Thus, the given program is implemented and executed successfully .
 


EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers
### Aim: 
To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
cube = lambda x: x**2 if x%2==0 else x**3
def fun(f,l):
     l1=[]
     for i in range(f,l+1):
           l1.append(i)
      return l1
f,l = int(input()),int(input())

```
### Output:
![image](https://github.com/user-attachments/assets/4a9076d8-a2cf-44e1-b7d1-e638b7edf12f)

### Result: Thus, the given program is implemented and executed successfully .
 
EXPTNO: 8e Reverse the sentence.

### Aim:
To Write a python program to print the sentence by reversing each word in sentence.

### Algorithm
Split the input string into words

reverse each word

print the reversed words separated by spaces.

### Program:
```
n=input().split()
for i in n:
    print(i[::-1],end=" ")
```

### Output :
![Screenshot 2025-06-02 135458](https://github.com/user-attachments/assets/90709047-b092-4cd4-85e2-93fbcbf91962)

### Result:
Thus, the given program is implemented and executed successfully .
