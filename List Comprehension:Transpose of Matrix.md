# 🧮 List Comprehension:Scalar multiple of a set of numbers

## 🎯 AIM:
To write a Python program to store a scalar multiple of a set of numbers  in a list using list comprehension.

---

## 🧠 ALGORITHM:

1. Read n (number of elements).
2. Read scl (scale factor).
3. Initialize empty list l.
For i = 1 to n:
4. Read a float x, append to l.
5. Compute sq_l = [item * scl for item in l].
6. Print l and sq_l.

---

## 💻 PROGRAM:
~~~
n=int(input())
scl=int(input())
l=[]
for i in range(n):
    x=float(input())
    l.append(x)
sq_l=[item*scl for item in l]
print(l)
print(sq_l)
~~~
    
    


## OUTPUT:
<img width="757" height="349" alt="image" src="https://github.com/user-attachments/assets/03cb3b47-015c-42fe-974b-380dd5f0684f" />


## RESULT:
Thus the output is verified.
