# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2: 
Enter a new file name to create a copy of a file content.
### Step 3: 
Read the file and close te file.
### Step 4:  
Now write te content in the new file.
### Step 5: 
Print "File copied successfully" when code is completed.
### Step 6: 
End of the program.
## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: Abbu Rehan
Register Number: 23010259

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![Screenshot (163)](https://github.com/Abburehan/copy-file/assets/138849336/9f969305-f0aa-46e6-963f-5733fd6aaabd)

![Screenshot (164)](https://github.com/Abburehan/copy-file/assets/138849336/e4e62c52-ede7-4219-8673-ef1f5e9c2773)

![Screenshot (165)](https://github.com/Abburehan/copy-file/assets/138849336/16e36ba9-8c3a-4343-96fa-801a58f96f87)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
