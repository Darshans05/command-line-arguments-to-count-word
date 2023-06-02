# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2: 
Open the file with sys.argv[1]
 
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words
## PROGRAM:
```python 
Program for getting the word count from the contents of a file using command line arguments
Developed by: DARSHAN S
RegisterNumber: 212222100010
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```

### OUTPUT:
![image](https://github.com/Darshans05/command-line-arguments-to-count-word/assets/115534676/86323891-5e40-4aae-857e-6b816d684410)
![image](https://github.com/Darshans05/command-line-arguments-to-count-word/assets/115534676/01f35d54-843f-476d-b099-6e2728b07ba2)
![image](https://github.com/Darshans05/command-line-arguments-to-count-word/assets/115534676/0ef318df-8f50-45ee-9922-9e06c4a2578f)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
