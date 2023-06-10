# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test moode.
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```python
"""
Program to count the words in a file
Reg No:212222110040
Name:Sanjeevi J
"""
fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print('Number of words:',num_words)
```
### OUTPUT:
![image](https://github.com/sanjeevi00/Word-count/assets/121484976/8d7acc0c-c90d-41e2-bd0a-714ad5fdea1a)

## RESULT:
Thus the program is written to find the word count from a text.
