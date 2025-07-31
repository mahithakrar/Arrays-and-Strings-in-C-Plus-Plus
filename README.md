# Arrays-and-Strings-in-C-Plus-Plus

#  Strings and Arrays in Programming

##  Overview

Strings and arrays are fundamental data structures used to store and manipulate collections of elements. Arrays are fixed-size collections of elements of the same data type, whereas strings are sequences of characters, often implemented as arrays of characters. Both play a crucial role in storing and processing data efficiently in almost every programming language.

Understanding strings and arrays is essential for working with data input/output, algorithm design, data manipulation, and memory management.

###  Arrays

- An **array** is a data structure that stores elements of the same type in contiguous memory locations.
- Elements in an array are accessed using **indexes** (starting from 0).
- Arrays can be:
  - **One-dimensional** (1D): Linear structure.
  - **Multidimensional** (2D, 3D...): Matrices or higher-dimensional tables.

Operations on Arrays:
Initialization
Traversal (looping)
Insertion
Deletion (by shifting)
Searching (Linear or Binary)
Sorting (Bubble, Selection, etc.)

Strings:
A string is a sequence of characters terminated with a null character (\0) in C/C++.

Strings can be:
Character arrays (C-style strings)
Objects of the string class (C++ STL)

Operations on Strings:
Concatenation
Length check
Comparision
Substring extraction
Searching
Insertion/Deletion

Key Differences:
Feature	Array	String
Data Type	Homogeneous elements	Sequence of characters
Memory	Fixed size	Dynamic (for C++ strings)
Termination	No special terminator	Ends with \0 (char array)
Use Case	Numbers, structures, etc.	Textual data

Program Summary:

##To check if a string is palindrome:

### What is a Palindrome?
A **palindrome** is a word, number, or sequence of characters that reads the same forward and backward.  
For example:
- "madam" → palindrome ✅  
- "level" → palindrome ✅  
- "hello" → not a palindrome ❌

Algorithm:
1.Start
2.Declare a string variable str1.
3.Prompt the user to enter a string.
4.Read the input string using cin.
5.Find the length of the string and store it in variable len.
6.Initialize a loop counter i to 0.
7.Repeat the following steps while i < len / 2:
  Compare the character at position i with the character at position len - i - 1.
  If the characters do not match:
  Exit the loop (string is not a palindrome).
  Otherwise, increment i and continue.
8.After the loop ends:
  If i == len / 2, then all characters matched — print that the string is a palindrome.
  Else, print that the string is not a palindrome.
9.End

##String Concatenation

### What is String Concatenation?
**String concatenation** is the operation of joining two or more strings end-to-end to form a new string. It is a fundamental operation when working with text data in programming.
In C++, string concatenation can be easily performed using the `+` operator if you're using the **`string` class** from the C++ Standard Library.

## Algorithm
1. **Start**
2. Declare a string variable `s1` for the first input string.
3. Prompt the user to enter the first string.
4. Read the first string using `cin >> s1;`.
5. Declare another string variable `s2` for the second input string.
6. Prompt the user to enter the second string.
7. Read the second string using `cin >> s2;`.
8. Declare a string variable `concatenate` to store the result.
9. Use the `+` operator to join `s1`, a space (`" "`), and `s2`, and assign it to `concatenate`.
10. Display the concatenated string.
11. **End**

 ### What is an Array?

An **array** is a collection of elements of the same data type stored in contiguous memory locations. Each element can be accessed using an index.

In this program:
- An integer array of size 5 is used.
- The user inputs 5 elements.
- The array is then displayed in both **original order** and **reverse order**.

## 📋 Algorithm

### 🎯 Objective:
To input 5 integers into an array and display them in both original and reverse order.


1. **Start**
2. Declare an integer array `arr[5]` to store 5 numbers.
3. Display a message prompting the user to input 5 integers.
4. **For** `i` from `0` to `4`:
   - Read an integer from the user using `cin`.
   - Store it in `arr[i]`.
5. Display a message: `"The numbers of array are:"`
6. **For** `i` from `0` to `4`:
   - Print `arr[i]` to display the array in original order.
7. **For** `i` from `4` down to `0` (i.e., reverse order):
   - Print `arr[i]` to display the array in reverse.
8. **End**

###Find Min and Max Number in an Array
  
## Theory
This program is designed to find the **minimum** and **maximum** values in a predefined array of integers using simple iteration and comparison techniques.

## 📋 Algorithm
1. **Start**
2. Declare an integer array `arr[5]` and initialize it with 5 values:
3. Declare two variables:
- `min` and initialize it with `arr[0]`
- `max` and initialize it with `arr[0]`
4. **For** `i` from `0` to `4` (loop through the array):
- **If** `arr[i] < min`:
  - Set `min = arr[i]`
- **If** `arr[i] > max`:
  - Set `max = arr[i]`
5. After the loop ends:
- `min` contains the smallest number in the array.
- `max` contains the largest number in the array.
6. Display the values of `min` and `max`.
7. **End**


Conclusion:
Arrays and strings are core building blocks in programming. Arrays offer a way to store and access multiple values efficiently using indices, while strings provide a method to handle text and characters with powerful manipulation capabilities. Mastering their usage is essential for solving real-world problems, implementing data structures, and developing algorithms. A solid grasp of these concepts lays the groundwork for more advanced topics like dynamic memory, pointers, and data structures like stacks and queues.



