### [Read & Write Files in Python](https://realpython.com/read-write-files-python/)

* 3 mainn parts of file: Header; Data; End of file(EOF)

* 3 major parts of file path: Folder Path; File Name; Extension

* double-dot(..) can traverse directories above the current directory

* Open & Close file:
  * file = open('dog_breeds.txt')
  * reader = open('dog_breeds.txt')
try:
    Further file processing goes here
finally:
    reader.close()

* .write(string): This writes the string to the file.

* The __file__ attribute is a special attribute of modules just like __name__

### [Exceptions in Python](https://realpython.com/python-exceptions/)

* How to raise, catch, and handle exceptions in Python

[<--Back](README.md)