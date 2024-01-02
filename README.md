# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
start the program
### Step 2: 
 Get the text from the user
### Step 3: 
Write the function to count the words
### Step 4:  
Type the program to get the output
### Step 5: 
Print the number of words
### Step 6: 
End the program
## PROGRAM:
```
#Program to find the word count
#Developed by: THEJASWINI
#Reference NUmber: 212223110059
num=0
with open("word.txt","r") as f1:
  for i in f1:
    word=i.split()
    num += len(word)
print("The number of words are in the file is ",num) 
```
### OUTPUT:
![image](https://github.com/thejaswinidhanaraj/Word-count/assets/148514511/7ce3e57d-d4c1-47c6-acf3-9d723eeda4c9)



## RESULT:
Thus the program is written to find the word count from a text.
