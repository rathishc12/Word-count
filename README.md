# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open terminal and activate conda, then open jupyter notebook.

Step 2:
Create a text file in jupyter notebook or upload a text file in the jupyter notebook.

Step 3:
Open a new cell in jupyter notebook.

Step 4:
Type the program in the cell.

Step 5:
Now in the output box,type the file name.

Step 6:
End the program

## PROGRAM:
```
fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/120539398/214815457-1192c342-efc8-4ec8-a7b6-0ea3e13af1df.png)



## RESULT:
Thus the program is written to find the word count from a text.
