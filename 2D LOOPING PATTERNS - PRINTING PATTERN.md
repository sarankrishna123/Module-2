# Exp.No:2d
## LOOPING PATTERNS - print inverted pyramid pattern of numbers Get the input for the number of rows  to be displayed .

---

### AIM  
To Write the program to print inverted pyramid pattern of numbers Get the input for the number of rows  to be displayed .

---

### ALGORITHM

1. Prompt the user to enter the number of rows for the inverted pyramid pattern.  
2. Read the input and convert it to an integer.  
3. Start a loop from the input number down to 1.  
4. In each iteration, print spaces equal to the difference between the total number of rows and the current row number.  
5. After the spaces, print numbers starting from 1 up to `2 * current row number - 1`.  
6. Move to the next line after printing each row.  
7. Repeat the process until all rows are printed.

---

### PROGRAM
```
#Reg.No:212223070023
#Name:Saran Krishna P S
rows = int(input())
b = 0

for i in range(rows, 0, -1):
    b += 1
    for j in range(1, i + 1):
        print(b,end=' ')
    print()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/46186539-c001-4783-a840-3bb4fa9021c1)

### RESULT
Thus the above program is executed successfully.
