# Task 1

## Question 1 
The mega data type contains 2 bytes or 16 bits.   
Since it is defined as the largest data type supported by the CPU and the maximum addressable width is 2 bytes, it follows that the mega data type is 2 bytes.

## Question 2
Create two functions, sum(), in separate namespaces, one returning integer data type and the other returning long.  
The purpose of this task is to demonstrate the use of namespaces in preventing same name clashes.  

## Question 3
The result of this code is 4294967295.  
On a 32 bit system, the range of an unsigned integer is 0 - (2^32) - 1, that is, 0 - 4294967295.  
Unsigned integers cannot be negative, so to have  code that executes 0 - 1, which would give an output of -1 would cause an overflow, and cause a wraparound, bringing the result back to the very last integer in the range, which is 4294967295. 
