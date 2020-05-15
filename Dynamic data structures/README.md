# Dynamic data structures
## 1.
Write a program to create a students’ list. The program should enable storing data on the dynamic
ordered list (one directional searching) and in BST. It should also allow adding an element to the
existing structure, searching for the element and deleting it from the structure. Each element
consists of a surname, first name and index number. (12 characters First Name, 12 characters Last
Name, 7 digits Index No.)
## 2.
Prepare data sets for testing the time needed for performing individual operations( add, search,
delete element) on the tested data structures. Such a set should contain n records (surname, first
name, index number), but only the index number will be treated as a key for operations performed
on data structures (Data to the input table read from a previously generated text file – the file should
be editable - not a binary file).
## 3.
Measure the time needed to add elements to the considered structures, data sets of different
sizes n, and to remove all elements (removing element one by one – elements for removing are
chosen randomly).
In addition, examine the time necessary to search elements in each of the structures ( function of n) -
by measuring the average search time of all elements in turn, if necessary run several turns).
In this case, you should compare the times of three following structures: the ordered list, BST and
Balanced BST (BBST). The element again should be selected randomly.
