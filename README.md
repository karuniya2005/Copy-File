# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open the text file that you want to copy
### Step 2: 
by using read function read the file 
### Step 3: 
now open the file that you want to store the copied text
### Step 4:  
by using write function write the file
### Step 5: 
now open the second file to see the copied text
## PROGRAM:
```
# program to copy text from one file to another
# NAME : Karuniya M
# Reg no : 212223240068
with open("text1.txt","r") as f1:
    msg1=f1.read()
with open("copy.txt","w") as f2:
    f2.write(msg1)
```
### OUTPUT:
![image](https://github.com/karuniya2005/Copy-File/assets/161425769/d688b24b-f67d-4aa5-9eb3-309cca5ede16)

![image](https://github.com/karuniya2005/Copy-File/assets/161425769/ad0f9d43-f97a-4fd8-8dbe-2c9e1553f941)

![image](https://github.com/karuniya2005/Copy-File/assets/161425769/445da799-3b78-4d9e-8436-e0656a5a3dd3)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
