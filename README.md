# Assignment 11 – STL List and Vector Containers in C++

## Student Details
- **Name:** Vaishnavi Bagad
- **Branch:** CSE – AI/ML
- **Batch:** B1
- **Institution:** MIT Academy of Engineering, Alandi

## Practical Title
Implementation of (a) List Class and (b) Vector Class as Containers of the Standard Template Library (STL) in C++.

## Aim
To implement and understand the `list` and `vector` containers of the C++ Standard Template Library (STL) and perform their basic operations.

## Problem Statement
**Part A – List:** Write a C++ program using the STL list class to store integers and perform operations such as `push_back()`, `push_front()`, `pop_front()`, `pop_back()`, `sort()`, `reverse()` and `remove()`.

**Part B – Vector:** Write a C++ program using the STL vector class to store integers and perform operations such as `push_back()`, `size()`, `front()`, `back()`, `insert()`, `erase()`, `sort()`, `pop_back()`, `at()` and `clear()`.

## Objectives
1. Understand the Standard Template Library (STL) and its containers.
2. Use the list container and its member functions.
3. Use the vector container and its member functions.
4. Use iterators to move through container elements.
5. Understand the difference between list and vector.

## Concepts Used
- **STL:** A ready-made C++ library containing containers, iterators and algorithms.
- **List:** A doubly linked list that supports insertion and deletion at both ends and does not provide direct index access.
- **Vector:** A dynamic array that stores elements in continuous memory and supports direct access using an index.
- **Iterator:** A pointer-like object used to traverse container elements.
- **Algorithm:** The `sort()` function is used to arrange vector elements in increasing order.

## Header Files
- `<iostream>`
- `<list>`
- `<vector>`
- `<algorithm>`

## Algorithm
1. Start the program.
2. Include the required header files.
3. Read three integers from the user.
4. Create a list and insert elements using `push_back()` and `push_front()`.
5. Display the list and its size.
6. Perform `pop_front()` and `pop_back()`.
7. Perform sorting, reversing and removing an element.
8. Create a vector and insert three integers using `push_back()`.
9. Display the vector, its size, first element and last element.
10. Insert an element at the beginning and erase the element at index 1.
11. Sort the vector and remove its last element.
12. Access an element using `at()`.
13. Clear the vector and display its size.
14. Stop the program.

## Sample Input
```text
30 10 20
```

## Sample Output
```text
--- LIST OPERATIONS ---
Original List: 0 30 10 20 99
Size of List: 5
After pop_front and pop_back: 30 10 20
After sorting: 10 20 30
After reversing: 30 20 10
After removing 10: 30 20

--- VECTOR OPERATIONS ---
Original Vector: 30 10 20
Size: 3
First Element: 30
Last Element: 20
After inserting 50: 50 30 10 20
After erasing index 1: 50 10 20
After sorting: 10 20 50
After pop_back: 10 20
Element at index 1: 20
Size after clear: 0
```

## Result
The program successfully demonstrated the operations of STL list and vector containers. All the specified operations were performed and the expected output was obtained.

## Conclusion
This practical helped understand the list and vector containers of the C++ Standard Template Library. A list is useful for frequent insertions and deletions, whereas a vector is useful when fast access by index is required. STL containers make programming easier by providing ready-made data structures and functions.

## Technologies Used
- Programming Language: C++
- IDE: Dev-C++
- Libraries: iostream, list, vector, algorithm

## Repository Structure
```text
Assignment11-CPP/
│
├── main.cpp
├── README.md
└── output.png
```

## GitHub Topics
`cpp` `cplusplus` `stl` `list` `vector` `containers` `dsa`
