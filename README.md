### **Data Structures and Algorithms.**

This repository contains over 200 data structures and algorithm questions and  their solution for interview preparation from different websites and Cracking the Coding Interview book by  Laakmann Gayle McDowell


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

---
2). Question 1: Write a program that finds the length of the last word.  

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
