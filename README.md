# Binary_Search_Tree
A program that demonstrates the use of a binary search tree to load, store, and sort through various data structures.
I was task in creating a program that will parse through csv files and load the information into structures and store those
structures into a sorting method of my choosing. The information contained college course that had information like course ID, course name, and any prerequisites.
After analyzing three methods to store information, I decided to use a binary search tree. Understanding each data structure, helps determine the run time complexity
of a program and helps decide which data structure works best for a program. I choose the binary search tree because it was the second fastest method, iun terms of run
complexity, but it was the simpliest in my opinion to apply. To begin we needed to store the information in structure that can hold all the information. I made a 
structure named course that will hold the course name, course ID, and created a vector that will hold all, if any, prerequisites the courses need. The hardest part of 
this project was understanding how to sort through the binary search tree. Once, understood everything fell into place. I had to create a method that would display
the courses by alphabetical order, but then search through them by course ID. Since a binary search tree is generally organized by one trait, I had to create a function
that would sort the binary search tree by the mode it required each time it was needed. I also had to keep in mind that, while my list of courses was short and had 
definite prerequisites I had to keep in mind that this csv file could expand and get smaller. To make sure my program worked despite changes, the prerequisites were
created into said vector, and I implemented a function to determine the size of the binary search tree to check the size before applying any sorting methods. Also, all
in all I made sure to comment on every possible function to make sure any one reading my code would be able to understand my methodology.
