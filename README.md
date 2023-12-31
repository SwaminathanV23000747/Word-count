# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode
### Step 2: 
Read the text using read() function. 
### Step 3: 
Split the text using space separator .we assume that words in a sentence are separated by a space character.
### Step 4:  
The length of the split list should equal the numbe of words in the text file.
### Step 5: 
You can refine the count by clearing the string prior t splitting or validatting the words after splitting
### Step 6: 

## PROGRAM:
```python
Developed by : Swaminathan V
Reference number: 23000747
num=0
with open("/content/swami.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
### OUTPUT:
![EX-05a 1](https://github.com/SwaminathanV23000747/Word-count/assets/148931113/c0ec3987-8f5a-4bab-80bc-48d68737eeba)
![ex-05a 2](https://github.com/SwaminathanV23000747/Word-count/assets/148931113/88e00558-314c-44de-aee2-09353d43b177)



## RESULT:
Thus the program is written to find the word count from a text.
