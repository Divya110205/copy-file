# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Open the file f1 in read mode.

### Step 2: 

Open the file f2 in append mode.

### Step 3: 

Copy the contents using write() with the for loop.

### Step 4:

End the program.
## PROGRAM:
```
# Ex5c Copy file
# Program Developed By: DIVYA.A
# Register Number: 212222230034
with open('f1.txt','r') as f1:
  with open('f2.txt','a') as f2:
    for line in f1:
      f2.write(line)
```
## f1:
![Exp 5c(1)](https://github.com/Divya110205/copy-file/assets/119404855/3c4b0d88-a6b7-4795-9614-81bcaa0e3926)

## f2:
![Exp 5c(2)](https://github.com/Divya110205/copy-file/assets/119404855/404685dd-6a03-42c7-81e4-b2c99005d7bc)

## OUTPUT:
![Exp 5c(3)](https://github.com/Divya110205/copy-file/assets/119404855/d88fa59a-eec9-4a70-9f38-0ef5e9f09731)

![Exp 5c(4)](https://github.com/Divya110205/copy-file/assets/119404855/0ad64fe7-4c95-40d6-bee7-9cee9e542597)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
