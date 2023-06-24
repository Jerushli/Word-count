# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open then required file by using the function"with"
### Step 2: Using split function to split the words.
### Step 3: Finding the length of the words by using len() function.
### Step 4: Calling the function and printing the number of words.
## PROGRAM:
```
#Developed by: JERUSHLIN JOSE JB
#Register No: 212222240039
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
for line in f:
words=line.split()
wordslen+=len(words)
print("Number of wordds:",wordslen)

```

### OUTPUT:
![Screenshot 2023-06-15 222338](https://github.com/AnandhamoorthyKarthikeyan/Word-count/assets/119475998/09f6c40f-9250-4a22-9d00-366bafa8578e)

## RESULT:
Thus the program is written to find the word count from a text.
