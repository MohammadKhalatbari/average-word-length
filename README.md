# average-word-length
This is an assignment from a Finnish company - This repository is temprorary.</br>
This program contains two Python files.</br>
<h3>AverageWordLength.py</h3>
This file contains the main function of the program.</br>
  In this function, first all characters except numbers and alphabetic letters are removed.</br>
  In the next part, all the words are separated from each other and placed in a list.</br>
  In the next part, all spaces are deleted.</br>
  Finally, all the letters are read and the length of the words is calculated and divided by the number of words.</br>
<h3>TestCases.py</h3>
Test cases are written in this file.</br>
In this file, all written examples are tested in case of questions. The assert method is used to write test cases.</br>
If the output value of the program does not match the desired number, the program displays the error and the correct value.
<h3>Metacharacters</h3>
1-. (dot): ANY ONE character except newline. Same as [^\n] </br>
2- \d, \D: ANY ONE digit/non-digit character. Digits are [0-9]</br>
3- \w, \W: ANY ONE word/non-word character. For ASCII, word characters are [a-zA-Z0-9_]</br>
4- \s, \S: ANY ONE space/non-space character. For ASCII, whitespace characters are [ \n\r\t\f]