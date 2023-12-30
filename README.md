# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open the file in read mode and handle it in text mode.
### Step 2: 
Read the text using read() function. 
### Step 3: 
Split the text using space separtor. we assume that Words in a sentence are separated by space character.
### Step 4:  
The length the split list should equal the numbers of the word in text file.
### Step 5: 
You can trefine the count by cleaning the string prior to splitting or validating the words after spitting.
### Step 6: 
End the program.
## PROGRAM:

```

Developed By: DIVYA E

Register Number: 212223230050
 
'''

def wordcount(filename):
count=0
with open(filename,"r") as f:
     for data in f:
         words=data.split()
         for word in words:
             count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```
### OUTPUT:
![Alt text](<word count 1.png>)
![Alt text](<word count 2.png>)

## RESULT:
Thus the program is written to find the word count from a text.
