# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
 Open the file with sys.argv[1]
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: PRAKASH M
RegisterNumber: 212222100035
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)

```

### OUTPUT:



![ex 5 w](https://github.com/Prakashmathi2004/command-line-arguments-to-count-word/assets/118350045/b38610ec-f7ac-4bb8-bc27-e4a90b6ae00f)

![wo re](https://github.com/Prakashmathi2004/command-line-arguments-to-count-word/assets/118350045/09c8f3ba-283d-4718-b550-fd415a0a9f25)

![ex 5-re](https://github.com/Prakashmathi2004/command-line-arguments-to-count-word/assets/118350045/186709e0-999d-40ec-afda-6e1c4502e23f)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
