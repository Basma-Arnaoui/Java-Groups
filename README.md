# Java-Groups
Task : Write a Java program that divides the students into groups of two by taking the number of students and their names as input and outputting the groups assigned to each project with no repetition of the groups.
  The number of students should be a power of 2 (MODIFIED).
  The number of projects should be (number_of_students - 1) * 2.
  
  --> Example:
4 Students & 6 Projects & 12 combination:


Input	

Enter number of students: 4

Enter the name of the 1 Student: A
Enter the name of the 2 Student: B
Enter the name of the 3 Student: C
Enter the name of the 4 Student: D

Project 1: A_B, C_D
Project 2: B_A, D_C
Project 3: B_C, A_D
Project 4: C_B, D_A
Project 5: C_A, B_D
Project 6: A_C, D_B

Note that the first name is the leader of the group so A-B is not the same as B-A.
