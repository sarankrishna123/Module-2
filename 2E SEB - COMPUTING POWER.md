# Exp.No:2e  
## SEB - find the sum of the series

---

### AIM  
To Python Program to find the sum of series 1+3+5+7.......+N .
---

### ALGORITHM

1. Prompt the user to enter the value of N.  
2. Read the input and convert it to an integer.  
3. Initialize a variable to store the sum with a value of 0.  
4. Use a loop to iterate from 1 to N with a step of 2 to cover only odd numbers.  
5. In each iteration, add the current odd number to the sum.  
6. After the loop ends, print the final sum.

---

### PROGRAM

```
Reg no: 212223070023
Name:Saran Krishna P S
a=int(input())    
sum=0
for i in range(1,a+1):
    if i%2!=0:
        sum+=i
print("The sum of the series = ",sum)

```
### OUTPUT
![image](https://github.com/user-attachments/assets/2d29ad9b-4447-4d58-9116-750fdb3fe070)

### RESULT
Thus the above program is executed successfully.

