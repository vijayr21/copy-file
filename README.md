# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:First we need to open the required the from which we need to copy the text.

### Step 2: Using keyword "with" to open the required file.
 
### Step 3: Again using the with keyword to open the empty file.

### Step 4: The empty file is open by using 'W' which is used to write only. 

### Step 5: The for function is used to take each line from the main file

### Step 6: Write() is used to write the lines of main file to the empty file or to the directed file.

## PROGRAM:
```
with open("text.txt","r") as f1:
    data=f1.read()
with open("data.txt","w") as f2:
    f2.write(data)
```
## TEXT FILE:
```
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```
## EMPTY FILE:
```
with open("data.txt","w") as fd:
 fd.write("")
```
## COPY FILE:
```
with open("data.txt","r") as f2:
  data1=f2.read()
  print(data)

### OUTPUT:
```
![1](https://github.com/vijayr21/copy-file/assets/149347607/f02da6e0-7ffe-4b51-94fc-e825fc134e63)
![2](https://github.com/vijayr21/copy-file/assets/149347607/4f294165-6d65-4d4d-8010-ee9da0a8e44e)
![3](https://github.com/vijayr21/copy-file/assets/149347607/629d8431-f1b8-4bfe-9404-0e46083e5843)
![4](https://github.com/vijayr21/copy-file/assets/149347607/afbe1440-0cad-4b24-b488-3c421604711a)
```





## RESULT:
Thus the program is written to copy the contents from one file to another file.
