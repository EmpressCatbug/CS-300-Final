# CS-300-Final
The repository here includes an analysis of runtime and memory usage of various data structures from Project One, as well as the source code for sorting and displaying Computer Science courses in alphanumeric order from Project Two.



**CS 300 Project 1: Data Structure Analysis**

This repository contains my analysis and implementation for Project One in the Computer Science program, focusing on data structures and their impact on runtime and memory efficiency. The project involves:

- **Vector Data Structure**: Implementation of a dynamic vector to manage a list of courses, including functions to load, validate, and print course information.
- **Hash Table Data Structure**: A robust hash table implementation to efficiently handle dynamic datasets, such as a course catalog.
- **Tree Data Structure**: Implementation of a binary search tree for ordered data management and efficient searching.

Each section contains pseudocode, a thorough evaluation of runtime and memory considerations, and practical implications of using each data structure in real-world applications. This project showcases my ability to apply theoretical concepts to solve practical problems, highlighting my growth in understanding and implementing efficient data structures.

### Reflections and Insights

**Problem Solving**: The main challenge was to manage course data effectively, ensuring quick access and updates. I needed to select appropriate data structures that could handle operations like insertion, deletion, and retrieval efficiently, considering both runtime and memory usage.

**Approach and Data Structures Importance**: I approached the problem by evaluating different data structures based on their theoretical and practical benefits. Understanding the characteristics of vectors, hash tables, and trees helped me choose the right tool for specific needs, such as maintaining ordered data with trees or ensuring fast access with hash tables.

**Overcoming Roadblocks**: During the project, I encountered challenges like handling large datasets and ensuring efficient memory management. I overcame these by refining my implementation and choosing data structures that could scale well with the size of the data, like using hash tables for their average-case time complexity benefits.

**Impact on Software Design**: This project expanded my approach to designing software by emphasizing the importance of choosing the right data structure for specific requirements. It has taught me to evaluate the trade-offs between ease of implementation, performance efficiency, and future scalability.

**Evolution in Development Practices**: Working on this project has evolved the way I write programs to be more maintainable, readable, and adaptable. Implementing different data structures and analyzing their performance has enhanced my ability to write clear and efficient code, considering not just the current requirements but also potential future changes.

This detailed examination and reflective insight into each data structure's application have significantly contributed to my professional development, equipping me with the skills to tackle complex software development challenges effectively.





**CS 300 Project 2: Advising Assistance Application**

This repository contains the source code and data for Project 2, part of the Computer Science program, which features an Advising Assistance application designed to sort and print out a list of courses in the Computer Science program in alphanumeric order. The application is implemented in C++ and makes use of several data structures, including vectors and maps, to efficiently manage course data.

### Application Overview

- **AdvisingAssistance.cpp**: This is the main C++ source file that contains the implementation of the course management system. It includes functionalities such as reading course data from a text file, storing it in appropriate data structures, and providing various utilities to interact with this data effectively.
- **Courses.txt**: Contains the list of courses along with their prerequisites formatted as CSV. This file serves as the input for populating the course data within the application.

### Features

- **Course Listing**: Sorts and displays all courses in the Computer Science program in alphanumeric order based on course numbers.
- **Prerequisite Checking**: Allows checking and displaying prerequisites for each course, ensuring that course dependencies are met.
- **Efficient Data Handling**: Uses maps and vectors to manage course data efficiently, facilitating quick lookups and modifications.

### Reflections and Insights

**Problem Solving**: The core problem addressed in this project was to create a tool that could assist students and advisors in managing and understanding the structure of the Computer Science curriculum, specifically focusing on the prerequisites and organization of courses.

**Approach and Data Structures Importance**: My approach involved developing a C++ application that reads and processes course data from a text file, using data structures like maps for quick data retrieval and vectors for ordered data storage. The choice of data structures was crucial for optimizing performance and ensuring the application could handle updates and queries efficiently.

**Overcoming Roadblocks**: One significant challenge was ensuring that the courses could be displayed in alphanumeric order while maintaining quick access to prerequisite information. This was addressed by integrating sorting algorithms and leveraging data structures that support efficient search operations.

**Impact on Software Design**: This project enhanced my understanding of software design, particularly in how data organization affects functionality and user experience. It emphasized the importance of modular design and the use of data structures that align with the application's goals.

**Evolution in Development Practices**: Through this project, I've improved my coding practices to prioritize code clarity, maintainability, and adaptability. It reinforced the importance of thorough testing and thoughtful design in developing software that is both efficient and easy to use.

### Usage

1. Clone the repository to your local machine.
2. Compile the C++ source using an appropriate compiler that supports the C++ Standard.
3. Run the compiled application and follow the on-screen prompts to interact with the course data.

### Objective

This project demonstrates the application of data structures in developing a practical tool that can assist students and advisors in managing course prerequisites and planning academic schedules effectively. It showcases my understanding of software development and algorithm implementation in C++.
