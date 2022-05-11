## **Data Structures and Algorithms.**

This repository contains over 200 data structures and algorithm questions and their solution for interview preparation from different websites and Cracking the Coding Interview book by  Laakmann Gayle McDowell

---
### **Day 1**
---

1). Question 1: Implement an algorithm using Python to determine if all characters in a string are unique, What if you can not use additional data structures. 

--- 

2). Question 2: Given two strings write a method to decide if one os a permutation or the other. 


```python 
def arePermutation(str1, str2):
     
    # Get lengths of both strings
    n1 = len(str1)
    n2 = len(str2)
 
    # If length of both strings is not same,
    # then they cannot be Permutation
    if (n1 != n2):
        return False
 
    # Sort both strings
    a = sorted(str1)
    str1 = " ".join(a)
    b = sorted(str2)
    str2 = " ".join(b)
 
    # Compare sorted strings
    for i in range(0, n1, 1):
        if (str1[i] != str2[i]):
            return False
 
    return True
 
# Driver Code
if __name__ == '__main__':
    str1 = "test"
    str2 = "ttew"
    if (arePermutation(str1, str2)):
        print("Yes")
    else:
        print("No")

```

--- 

3). Question 3: Write an algorithm such that if an element in a MxN matrix is O, it entire row and column is set to 0. 


--- 
4). Question 4: Implement an algorithm to find the 4th to the last element of a singly linked list. 


--- 

5). Question 5: Write code to remove duplicates from an unsorted linked list. How would you solve this problem if a temporary buffer is not allowed? 



--- 

### **Day 2**

---
1). Question 1: Write a program that finds the length of the last word.  

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

2). Question 2: Implement a function to check if a linked list is a palindrome( example of a palindrome is madam). 

--- 

3). Question 3:  Given a linked list which might contain a loop, implement an algorithm that returns the node at the beginning of the loop (if one doesn’t exist)  

---


4). Question 4: Explain how you could use a single array to implement three stacks. 


---

5). Question 5: Given a sorted (increasing order) array with unique integer elements, write an algorithm to create a binary search tree with minimal height. 

---  

### **Day 3**

---











