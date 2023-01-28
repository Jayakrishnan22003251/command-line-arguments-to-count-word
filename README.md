# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
  import sys
### Step 2: 
  Initially make count = 0
### Step 3: 
  Open the content file using command line arguments.
### Step 4:  
  By using for loop name the function as "line"
### Step 5: 
  Split the line using .split
### Step 6: 
  Count the length of the word and print it
## PROGRAM:

```
#Program to count number of words in a text file using command-line arguments 
#Developed by:Jayakrishnan L B L
#ROLL NO:22003251
import sys
count=0
with open(sys.argv[1],'r') as f:
        for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)

```
### OUTPUT:
![image](https://user-images.githubusercontent.com/120232371/215278499-b6c7fd01-c91f-452a-b809-6e271dfa8f82.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
