# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.
### Step 2: 
 Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.

## PROGRAM:
```
# program for copying the contents from one file to another file.
# Developed by:Ashwath M
# Reference number:212223230023
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### File:
![image](https://github.com/Reklies/copy-file/assets/147139232/d700a62d-7f98-4dbb-a504-b1f671bc5dab)
### Output
![image](https://github.com/Reklies/copy-file/assets/147139232/75f1f1d1-ada6-486f-ba94-f51d1b66f622)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
