# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words as 0.
### Step 2: 
Open the txt file for reading 
### Step 3: 
Create a range function for the file.
### Step 4:  
Then next, split the words by space.
### Step 5: 
Count the number of words
### Step 6: 
End the program by printing the output.
## PROGRAM:
```
# program to find the number of words in a text file
# Developed by : VIDHIYA LAKSHMI S
# Register number : 212223230238
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)      

```
## OUTPUT:

![image](https://github.com/saravidhya/Word-Count/assets/87062069/5dd85dac-66e2-4c15-8494-d23d3d045745)

## RESULT:
Thus the program is written to find the word count from a text.
