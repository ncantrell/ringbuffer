# ringbuffer 
Ringbuffer impplementation for PIC10C Spring 2018 (Homework Assignment 3)

# Process
This homework problem was pretty straight forward: grab the assignment description from CCLE and get to work.

I ended up using cpp.sh to work on the code. My workflow was to divide and conquer the work of converting the provided example code into a completed implementation.

# Problems, Solutions and Problem Solving
One problem I faced when working on this problem was understanding when the program was working entirely correctly vs. partially working. The other problem was getting "iterator end()" to work as intended so that the "for ( auto it = rq.begin() ; it != rq.end() ; ++it )" didn't result in an endless loop. 

## Solution 1) 
I found it was easier to understand the program output if I went back and reread the assignment description more carefully line by line.

### Solution 2) 
The solution to this problem has been a WIP since the project was due. I believe that drawing a picture and making predictions about the outputs vs. what the outputs actually are may provide some help in making this block of code work.


# Future Work
I would enjoy attempting to reimplement the ringbuffer from this assignment using a C++ queue or linked list instead of an array.
