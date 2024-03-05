# Week 6 Coding Activity

## What we will do
We will create a short program that practices arrays, input, and loops. We will hard code the number of students, but it can be worked to comply with any amount of students.

At the end there will be review questions. Please answer these with a partner, and record your answers in the responses.txt file included in this folder.

## Starter Code
```
/*
    CS-11 SI '24, codingActivity.cpp
    Purpose: Get some practice with getline() vs. cin, loops, and arrays.

    @author Your Name
    @version 1.0  00/00/2024
*/

#include <iostream>
using namespace std;

int main() {

    return 0;
}
```

## Steps

1. Ask the user to input how many students. Create two arrays of that size to store their names, and their ages. To make things simpler, we will always have 2 students.

2. Ask the user for the name and age of each student and store them. Name can be first and last name or just one of the two.

Example Output:
```
Enter the number of students: 2
Enter name of student 1: Alice
Enter age of student 1: 20
Enter name of student 2: Bob Smith
Enter age of student 2: 22
```

3. Now we will print all the students and their age in a list.

Example Output:
```
Enter the number of students: 2
Enter name of student 1: Alice
Enter age of student 1: 20
Enter name of student 2: Bob Smith
Enter age of student 2: 22

Student List:
1. Alice - 20
2. Bob Smith - 22
```

### Review Questions (answer in txt file):
* Did you run into any problems when reading in the input?
* Did you use cin, getline(), or a combination of both? Why?
* Do you think there may be some advantages to using one over the other?
* Does it matter where you place the ```cin >> ws``` statement?
* How can we update the code so that it will work with any number of students?
