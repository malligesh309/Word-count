# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open the file as a read mode
### Step 2: 
assgin a variable to store the data
### Step 3: 
using f.read().split() and storing that in assgined variable as x
### Step 4:  
y=len(x)
### Step 5: 
print the number of words y
### Step 6: 
End the program
## PROGRAM:
```
#to find no.of words in the csv file
#Developed by : MALLIGESH M
#Register number : 23002936

from google.colab import drive
drive.mount('/content/drive')

f=open("/content/drive/MyDrive/python/python.txt",'r')
x=f.read().split()
y=len(x)
print("Number of words :",y)
```
### OUTPUT:
![output](/out.png)
![output](/txt.png)


## RESULT:
Thus the program is written to find the word count from a text.
