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
  Python script to print
  1. first 3 letters of the variable
  2. last 2 letters of the variable
  3. the value of the variable without the first and last letters
```
word = "Holberton"
word_first_3 = word[0:3]
word_last_2 = word[7:9]
middle_word = word[1:8]
print("First 3 letters: {}".format(word_first_3))
print("Last 2 letters: {}".format(word_last_2))
print("Middle word: {}".format(middle_word))
```