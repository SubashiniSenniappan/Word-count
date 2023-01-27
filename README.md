# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
        To write a python program for getting the word count from a text file

### Step 2: 
         open the required file by using the function "with"
 
### Step 3: 
         them use the laptop to assign the value in the file

### Step 4:
         using spilt()
       
### Step 5:
        finding the given length of the words by using len() function

### Step 6:
         calling the function and printing the number of words

## PROGRAM:
```
#Developed by S.Subashini
fname = input("Enter file name:")
num_words = 0
with open(fname,"r") as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print("Number of words:",num_words)
```

###OUTPUT:
  
  

![Screenshot_20230127_180458](https://user-images.githubusercontent.com/119404951/215101276-3294c72d-cb40-4838-b5cf-6272476c8d8a.png)


## RESULT:
Thus the program is written to find the word count from a text.
