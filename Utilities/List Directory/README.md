#  List Items in Directory
Simply list all files in a folder. 


## Getting started
Have python installed, download the py script and configure the folder paths. 
The printout will appear in your python console.  

##  Prerequisites
 - One built-in package to import
```python
from os import listdir
```

- Set the folder you want all the files from: 
```python
files_in_directory = listdir(r"C:\Users\<username>\Desktop\FILE_PATH_GOES_HERE")
```

##  Full Code

```py
from os import listdir

files_in_directory = listdir(r"C:\Users\<username>\Desktop\FILE_PATH_GOES_HERE")

for item in files_in_directory:
    print(item)
```
