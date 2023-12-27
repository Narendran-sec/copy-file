# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
use open function to open the file in which we want to copy from and access it in read mode
### Step 2: 
 read the file and store it in a variable
### Step 3: 
now create a file in which we want topaste the content using write acces mode
### Step 4:  
use write function to copy the read file that has been stotred in the varible
### Step 5: 
the content in the original file will be copied in the new file
### Step 6: 
End the program
## PROGRAM:
```

with open("Files.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line = f1.read()
        f2.write(line)

```
### OUTPUT:

![Screenshot (25)](https://github.com/Narendran-sec/copy-file/assets/147473131/88d6eb33-a3a4-4e66-96d7-dee86459434c)

![Screenshot (26)](https://github.com/Narendran-sec/copy-file/assets/147473131/61b6a41f-fc14-42bb-b777-39ca880deb57)

![Screenshot (27)](https://github.com/Narendran-sec/copy-file/assets/147473131/0518e17a-2b7e-445b-a26b-ac53e7aa41d1)







## RESULT:
Thus the program is written to copy the contents from one file to another file.
