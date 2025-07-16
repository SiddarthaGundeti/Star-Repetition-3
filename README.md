# Star-Repetition-3

write a program that reads a word and prints stars (*) equal to the length of the word.

Input: qwerty@2020

Output: q********0

Question Explanation:
The program is developed to transform a given string in a specific way:

i.Retain the first and last characters of the string.
ii.Replace all other characters in the string with asterisks (*).


Logical Approach:

1.Read Input:
Accept a string from the user.

2.Extract First and Last Characters:
Retrieve the first character of the string. This is done by accessing the first element of the string array (word[0]).
Similarly, retrieve the last character of the string using word[-1]. In Python, negative indexing starts from the end of the list, so -1 refers to the last element.

3.Replace Middle Characters with Asterisks:
Determine the number of asterisks to be inserted. This is done by calculating the length of the string minus two (to exclude the first and last characters) using len(word) - 2.
Create a string of asterisks of this length.

4.Concatenate and Output:
Concatenate the first character, the string of asterisks, and the last character to form the final result.
Output this result.

Example for Clarity:

If the input string is qwerty@2020:
The first character is q and the last character is 0.
The string length is 10, so the number of asterisks needed is 8.
Concatenating these, we get q + ******** + 0 = q********0
The output will be: q********0
