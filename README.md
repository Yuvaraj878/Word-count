# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we want to create a text file.
### Step 2: 
Then we want to create a python file. 
### Step 3: 
In that python file we want to write apython code to display
a word count.
### Step 4:  
We want to use commant with Open in that type that saved text file.
### Step 5: 
Then write a revelant program.

## PROGRAM:
### To write a python program for getting the word count from a text.
```python
#Developed By : YUVARAJ.S
#Register Number : 22008589
num_words =0
with open('text2.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
![output](./5a%201.jpeg)
![output](./5a%202.jpeg)


## RESULT:
Thus the program is written to find the word count from a text.
