### **Data Structures and Algorithms.**

This repository contains over 200 data structures and algorithm questions and their solution for interview preparation from different websites and Cracking the Coding Interview book by  Laakmann Gayle McDowell


---

1). Question 1: Implement an algorithm using Python to determine if all characters in a string are unique, What if you can not use additional data structures. 

--- 

2). Question 2: Given two strings write a method to decide if one os a permutation or the other. 

--- 

3). Question 3: Write an algorithm such that if an element in a MxN matrix is O, it entire row and column is set to 0. 


--- 
4). Question 4: Implement an algorithm to find the 4th to the last element of a singly linked list. 


--- 

5). Question 5: Write code to remove duplicates from an unsorted linked list. How would you solve this problem if a temporary buffer is not allowed? 



--- 

6). Question 6: Write a program that finds the length of the last word.  

**Solution : Python3** 

```python 
def length_of_last_word(s):
        words = s.split()
        if len(words) == 0:
            return 0
        return len(words[-1])

print(length_of_last_word("Python Exercises"))
print(length_of_last_word("Python"))
print(length_of_last_word(""))
print(length_of_last_word("  "))

#Output: 
#9
#6
#0
#0

```
----
