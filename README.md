# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
### Step 1:
Open visual studio code or jupyter lab.

### Step 2:
Create file with .py extension.

### Step 3:
Also create .txt file and input sentences.

### Step 4:
Write the code.

### Step 5:
Run the program.

### Step 6:
Print the values and end the program.

## PROGRAM:
```
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY : KARNAN K
## REFERENCE NO : 22003223
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```
### OUTPUT:

![WhatsApp Image 2023-01-29 at 14 33 17](https://user-images.githubusercontent.com/118787064/215316222-607f2859-2e09-42d9-9b73-f0b3e2a616e3.jpg)
![WhatsApp Image 2023-01-29 at 14 33 17 2](https://user-images.githubusercontent.com/118787064/215316233-9ee5b6db-d01e-413c-910b-675898773536.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
