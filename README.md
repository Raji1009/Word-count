# Word-count
## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.

### Step 2: 
Read the text using read() function.
 
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 4:  
The length of the split list should equal the numbers of words in the test file.

### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: 
End the program

## PROGRAM:
```
# Python program for getting the word count from a text
# developed by : Rajalakshmi R
# Reg no : 212223110037

num_words=0
with open("file1.txt","r") as f1:
    for i in f1:
        word=i.split()
        num_words+=len(word)
print("Number of words in the file = {}".format(num_words))
```

### OUTPUT:

![Screenshot 2023-12-29 210345](https://github.com/Raji1009/Word-count/assets/89059861/af994c8c-845f-4baa-8609-430030032f18)

![Screenshot 2023-12-29 210816](https://github.com/Raji1009/Word-count/assets/89059861/141fa31d-e1b4-46f2-bddb-9aff1f51c51a)

![Screenshot 2023-12-29 210352](https://github.com/Raji1009/Word-count/assets/89059861/547a4584-9727-48a6-a2a8-1e34ac9489d7)

## Result :
The program to find the word count is successfully completed
