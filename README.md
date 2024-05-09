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
![1ee5f3ce-5fd0-41f8-9be5-dddc1d13cd4f](https://github.com/Hemaatchu/Word-Count/assets/147328300/d1a26c80-4871-4846-860f-f269a450635d)

## RESULT:
Thus the program is written to find the word count from a text.
