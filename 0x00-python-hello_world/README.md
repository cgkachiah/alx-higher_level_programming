#A simple code to print Hello ALX

`print("Hello ALX")`

  Running a python script

`python3 "$PYFILE"`

  Running python code

`python3 -c "$PYCODE"`

  Python script to print exactly a particular text

`print("\"Programming is like building a multilingual puzzle")`

  Python script to print an integer stored in a variable
```
number = 98
print("{:d} battey street" .format(number))
```
  Python script to print a float with only 2 digits stored in a variable
```
number = 3.14159
print("Float: {:.2f}" .format(number))
```
  Python script to print a string 3 times and the first 9 characters of the string stored in a variable
```
str = "Holberton School"
print("{:s}{:s}{:s}" .format(str, str, str))
print("{:.9}" .format(str))
```
  Python script to concatenate and print two seperate variables
```
str1 = "Holberton"
str2 = "School"
str1 += " " + str2
print("Welcome to {}!".format(str1))
```