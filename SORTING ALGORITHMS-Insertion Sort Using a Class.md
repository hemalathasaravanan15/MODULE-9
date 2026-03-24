# 🧮 SORTING ALGORITHMS: Insertion Sort Using a Class

This program demonstrates how to implement the **Insertion Sort algorithm** using a Python class. It allows the user to input a list of numbers, sorts them using the insertion sort technique, and displays the sorted list.

---

## 🎯 Aim

To develop a Python class with functions to:
- Create a list of integers
- Sort it using the **Insertion Sort** algorithm
- Display the sorted list

---

## 🧠 Algorithm

1. **Start the program**
2. **Define a class** `InsertionSorter`
3. Inside the class:
   - `create_list()`:
     - Read number of elements
     - Store them in a list
   - `insertion_sort()`:
     - Iterate from the second element to the end
     - Move elements greater than the key to one position ahead
     - Insert the key at the correct position
   - `print_list()`:
     - Print the sorted list
4. **Create an object** of the class
5. **Call** the methods in order: `create_list()`, `insertion_sort()`, and `print_list()`
6. **End the program**

---

## 💻 PROGRAM:
~~~
class Numbers:
    def __init__(self):
        self.lst = []

    def create_list(self):
        n = int(input())
        self.lst = [int(input()) for _ in range(n)]

    def sorting(self):
        n = len(self.lst)
        for i in range(n):
            for j in range(0, n - i - 1):
                if self.lst[j] > self.lst[j + 1]:
                    self.lst[j], self.lst[j + 1] = self.lst[j + 1], self.lst[j]

    def print_List(self):
        for num in self.lst:
            print(num)
~~~

## OUTPUT:
<img width="712" height="529" alt="image" src="https://github.com/user-attachments/assets/fd966b19-c7bb-4fed-835f-6111e90bec08" />


## RESULT:
Thus the output is verified.
