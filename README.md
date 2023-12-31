# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Read the file using read() method.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Use len() to find the total words.
## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed by: prem kumar g
# Register number: 23003614
import sys
fp= open(sys.argv[0])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![Screenshot 2023-12-31 172557](https://github.com/PremkumarG3/command-line-arguments-to-count-word/assets/138955646/ca74b3ae-dfc4-41ad-84b3-df103baf890f)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
