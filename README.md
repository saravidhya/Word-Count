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
# Program to find the word count
# Developed by: HEMAVATHY.S
# register number: 212223230076
num=0
with open("/content/story.txt","r") as f1:
  for i in f1:
    word=i.split()
    num+=len(word)
print("The number of words in the file is ",num)

```
## OUTPUT:
![34675a8e-0387-4715-bd3b-1465623067c7](https://github.com/Hemaatchu/Word-Count/assets/147328300/25022606-3bd5-4532-b0bd-abec17258e38)



## RESULT:
Thus the program is written to find the word count from a text.
