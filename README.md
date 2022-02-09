# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create two files with extension .py and .txt
### Step 2: 
Import sys in the file with .py extension 
### Step 3: 
Give some input words in the file with .txt extension
### Step 4:  
Save the files
### Step 5: 
Open terminal
### Step 6: 
Run the program and get the output
## PROGRAM:
~~~
##Program Developed by : K.Balaji
##Reference number: 21005757
##To write a python program for getting the word count from the contents of a file using command line arguments.
import sys
count = 0
with open(sys.argv[1], 'r') as f:
    for line in f:
        word = line.split()
        count += len(word)
print("Word count in file = ", count)        
~~~


### OUTPUT1:
![output](./1.png)

### OUTPUT2:
![output](./2.png)

### OUTPUT3:
![output](./3.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
