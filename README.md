# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:Create a text1.txt with some content in it
Step 2: Open the text1.txt file in read mode
Step 3:Create a copy.txt file using write mode
Step 4: Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Programmed By:MURALI S
RegisterNumber: 212222230088
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![KM](https://github.com/MURALI22008445/copy-file/assets/119643767/a2269c1f-698d-4315-9dfa-98e3235bf5d8)
![KMM](https://github.com/MURALI22008445/copy-file/assets/119643767/4b649642-b7d4-4b7d-a785-ce7972427d17)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
