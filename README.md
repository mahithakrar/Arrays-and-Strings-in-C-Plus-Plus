# Arrays-and-Strings-in-C-Plus-Plus

//NAME:MAHI THAKRAR

//PRN:24070123056

//ENTC A3


# Strings and Arrays in Programming

## Overview
Strings and arrays are fundamental data structures used to store and manipulate collections of elements.  
- **Arrays** are fixed-size collections of elements of the same data type stored in contiguous memory locations.  
- **Strings** are sequences of characters, often implemented as arrays of characters.  

Both play a crucial role in storing and processing data efficiently in almost every programming language.

Understanding strings and arrays is essential for working with data input/output, algorithm design, data manipulation, and memory management.

---

## Arrays

- An **array** stores elements of the same type in contiguous memory locations.
- Elements are accessed using **indexes** (starting from 0).
- Arrays can be:
  - **One-dimensional** (1D): Linear list of elements.
  - **Multidimensional** (2D, 3D...): Matrices or higher-dimensional tables.

### Common Operations on Arrays:
- Initialization  
- Traversal (looping through elements)  
- Insertion  
- Deletion (by shifting elements)  
- Searching (Linear or Binary)  
- Sorting (Bubble sort, Selection sort, etc.)  

---

## Strings

- A **string** is a sequence of characters terminated with a null character (`\0`) in C/C++.
- Strings can be represented as:
  - Character arrays (C-style strings)
  - Objects of the `string` class (C++ STL)

### Common Operations on Strings:
- Concatenation  
- Length check  
- Comparison  
- Substring extraction  
- Searching  
- Insertion/Deletion  

---

## Key Differences Between Arrays and Strings

| Feature       | Array                         | String                          |
|---------------|-------------------------------|--------------------------------|
| Data Type     | Homogeneous elements           | Sequence of characters          |
| Memory        | Fixed size                    | Dynamic size (for C++ `string`)|
| Termination   | No special terminator         | Ends with `\0` (for char arrays)|
| Use Case      | Numbers, structures, etc.     | Textual data                    |

---

# Program Summaries and Algorithms

## 1. Check if a String is Palindrome

### What is a Palindrome?
A **palindrome** is a word, number, or sequence that reads the same forward and backward.  
Examples:  
- `"madam"` → palindrome ✅  
- `"level"` → palindrome ✅  
- `"hello"` → not a palindrome ❌  

### Algorithm:
1. Start  
2. Declare a string variable `str1`.  
3. Prompt user to enter a string.  
4. Read input string using `cin`.  
5. Find length `len` of the string.  
6. Initialize loop counter `i` to 0.  
7. While `i < len/2`:  
   - Compare `str1[i]` with `str1[len - i - 1]`.  
   - If they do not match, conclude it is **not a palindrome** and exit.  
   - Else, increment `i`.  
8. If all characters match, conclude it **is a palindrome**.  
9. End  

---

## 2. String Concatenation

### What is String Concatenation?
Joining two or more strings end-to-end to form a new string.  
In C++, the `+` operator concatenates strings when using the `string` class.

### Algorithm:
1. Start  
2. Declare string variable `s1`.  
3. Prompt and read first string `s1`.  
4. Declare string variable `s2`.  
5. Prompt and read second string `s2`.  
6. Concatenate using `concatenate = s1 + " " + s2`.  
7. Display the concatenated string.  
8. End  

---

## 3. Array Input and Display in Original and Reverse Order

### Description:
- Input 5 integers into an array.  
- Display elements in the original order.  
- Display elements in reverse order.

### Algorithm:
1. Start  
2. Declare integer array `arr[5]`.  
3. Prompt user to input 5 integers.  
4. Loop `i` from 0 to 4:  
   - Read integer into `arr[i]`.  
5. Display message `"The numbers of array are:"`  
6. Loop `i` from 0 to 4:  
   - Print `arr[i]` (original order).  
7. Loop `i` from 4 down to 0:  
   - Print `arr[i]` (reverse order).  
8. End  

---

## 4. Find Minimum and Maximum Number in an Array

### Theory:
Find smallest and largest values in an integer array by iterating and comparing elements.

### Algorithm:
1. Start  
2. Declare integer array `arr[5]` with initial values.  
3. Initialize `min = arr[0]`, `max = arr[0]`.  
4. Loop `i` from 0 to 4:  
   - If `arr[i] < min`, assign `min = arr[i]`.  
   - If `arr[i] > max`, assign `max = arr[i]`.  
5. After loop ends, `min` and `max` hold the smallest and largest values.  
6. Display `min` and `max`.  
7. End  

---

## Conclusion
Arrays and strings are core building blocks in programming.  
- **Arrays** provide efficient storage and access to multiple values using indices.  
- **Strings** enable handling and manipulation of textual data.  
Mastering these concepts is essential for solving real-world problems, implementing data structures, and developing algorithms. They form the foundation for advanced topics such as dynamic memory, pointers, and complex data structures like stacks and queues.
