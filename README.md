# my_list
# Python List Operations Demo

## Description
This Python script demonstrates fundamental list operations including:
- Creating and modifying lists
- Adding/removing elements
- Sorting and searching
- Using common list methods

## Script Code
```python
# Initialize empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert element at position 1
my_list.insert(1, 15)

# Extend with more elements
my_list.extend([50, 60, 70])

# Remove last element
my_list.pop()

# Sort the list
my_list.sort()

# Find and display index of 30
print("Index of 30:", my_list.index(30))
print("Final list:", my_list)
