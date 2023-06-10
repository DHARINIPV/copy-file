# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
''' 
Program for copying the contents from one file to another file
Programmed By: Dharini PV
RegisterNumber: 212222240024
'''
```
with open('f1.txt','r') as firstfile:
    with open('f2.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:

![Screenshot 2023-06-11 010329](https://github.com/DHARINIPV/copy-file/assets/119400845/87158b33-dbaa-46c3-9815-3ad48b1e9e13)

![image](https://github.com/DHARINIPV/copy-file/assets/119400845/6598beb0-0f18-444e-b436-306794af98c8)

![image](https://github.com/DHARINIPV/copy-file/assets/119400845/8441c34e-2c69-4e7c-82f3-8a8b2cc14cba)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
