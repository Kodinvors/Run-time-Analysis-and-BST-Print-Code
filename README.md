# Run-time-Analysis-and-BST-Print-Code

What was the problem you were solving in the projects for this course?
In this class we were tasked with identifying the most useful data structure to use in a program that sorts courses in alphanumeric order. The user should be able to quickly load the given courses from a given file and print the data for all of the courses as well as individual course information and any prerequisite classes required for a given course.

How did you approach the problem? Consider why data structures are important to understand.
To decide which data structure was most appropriate for this project I performed an analysis of several common data structures. In this course we examined vectors, hashtables, and binary search trees. The binary search tree data structure had the distinct advantage of being sorted during creation and as each additional node is added. This is ideal for a program that needs to quickly print an array in order. While a vector may be able to print in order, it must first be sorted. A hash table could provide a quicker option for searching, the disadvantages present in potential collisions and the unnecessary use of space make it a less desirable option than a binary search tree.

How did you overcome any roadblocks you encountered while going through the activities or project?
I hit several roadblocks in understanding how powerful recursive calls could be. I had to spend a lot of time thinking through how each recursion would need to fully resolve before moving on to the next. Perhaps the most surprising part was how many times recursion takes place within a binary search tree.

How has your work on this project expanded your approach to designing software and developing programs?
Learning about additional types of data structures opens up new ways to store and access data. In working with these data structures I have learned that more data structures can be created by a programmer to fit the needs of their project. Understanding how each of these types operates gives a strong base to begin thinking about additional useful and creative ways to store data. I also really appreciated learning about how to perform runtime analysis. The cost of code is a popular topic among programmers and before dipping into the topic in this class, it was hard to understand how various costs were calculated.

How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
A deeper understanding of data structures means that I can think critically about the way I choose to store and access data. Selecting a data structure that supports the goals of the project and is easily understood by other programmers who may need to update or maintain the code is a crucial part of any projects design. Care should be taken when thinking through which data structures to implement to avoid things like collisions, unnecessary comlexity, and the addition or removal of elements.
