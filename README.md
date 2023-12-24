# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a txt file to count the number of word in that file.
### Step 2: 
Open the txt file in read mode using with open().
### Step 3: 
Using split() function to split the words in the txt file and count it.
### Step 4:  
Save the python program using .py extention.
### Step 5: 
Run the python program in terminal to get the output.
### Step 6: 
Number of words in the txt file is displayed as the output.

## PROGRAM:
```
#Program to find number of words in a text file 
#Developed By: PRIYAADARSHINI.K
#Register no : 23000629

with open("wordcount.txt","r") as f:
    r=f.read().split()
    print(len(r))
```

### OUTPUT:
![output](/output.png)
![output](/output2.png)

## RESULT:
Thus the program is written to find the word count from a text.
