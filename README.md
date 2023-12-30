# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.
### Step 2: 
 Using keyword "with" to open the required file.
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The for function is used to take each line from the main file.
### Step 6: 
Write() is used to write the lines of main file to the empty file or to the directed file.
## PROGRAM:
```
##DEVELOPED BY: BHAVATHARANI S
## REFERENCE NUMBER: 212223230032
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:
![output](./sample1output.png)
![output](./sample2output.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.