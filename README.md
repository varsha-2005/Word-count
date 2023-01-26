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
Open the txt file in read mode using open().
 
### Step 3: 
Using split() function to split the words in the txt file and count it
Step

### Step 4:  
Run the python program to get the output.
### Step 5: 
Number of words in the txt file is displayed as the output.

### Step 6: 
output got
## PROGRAM:
Developed by : Varsha.G

Register Number : 22002003
```
fname = input('Enter file name: ')
num_words=0
with open(fname,'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print('Number of words: ',num_words)
```
### OUTPUT:
!['OUTPUT'](/WORDCOUNT.png)


## RESULT:
Thus the program is written to find the word count from a text.
