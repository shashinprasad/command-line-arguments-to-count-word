# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:Import sys module.
## Step 2: Open the file with sys.argv[1].
## Step 3: Use the for loop to select the content in file.
## Step 4:Use split function to to separate the file content into words or strings.
## Step 5: Count the length of the words using len.
## Step 6:Count the length of the words using len.
## PROGRAM:
```
'''
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: S.Shashin prasad
RegisterNumber:212222230144
'''
import sys
count=0
fp=open(sys.argv[1],'r')
for line in fp:
    list1=line.split()
    count+=len(list1)
print("no of words in a file",count)
```

### OUTPUT:

![WhatsApp Image 2023-06-14 at 14 54 49](https://github.com/shashinprasad/command-line-arguments-to-count-word/assets/129143499/adedd6fa-7bf1-4670-aa87-8225edb42168)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
