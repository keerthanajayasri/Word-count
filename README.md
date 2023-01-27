# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
#### Step 1:Open the file in read mode and handle it in test mode.

#### Step 2:Read the text using read() function.
 
#### Step 3:Split the text using space separator.We assume that words in a sentance are separted by a space character. 

#### Step 4:The length of the split list should equal the numbers of words in the test file.  

#### Step 5:You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6:End the program. 

## PROGRAM:
```
Developed by:keerthana jayasri s k
Register Number:22006582
with open("word.txt","w+") as f1:
    f1.write("A friend means well, even when he hurts you....")
    f1.write("birds of a feather flock together")
    f1.write("A friend in need is a friend indeed")
with open("word.txt","r")as f:
    data=f.read()
    x=data.split()
    print("number of word:",len(x))
      
```

### OUTPUT:

![image](https://user-images.githubusercontent.com/121163440/215140214-fa0b6e85-74db-482a-b314-e37cfec84c0a.png)


## RESULT:
Thus the program is written to find the word count from a text.
