# # ➖ Matrix Operations-display the lower triangle matrix

## 🎯 AIM:
To write a Python program to read a matrix and display the lower triangle Matrix
---

## 🧠 ALGORITHM:

1. Input n (size of square matrix).
2. Initialize an n × n matrix.
3. For each row, read n integers and store them in the matrix.
4. Print "Matrix:".
5. For each element M[i][j]:
If i ≥ j, print M[i][j].
Else, print 0.
6. Move to a new line after each row.

---

## 💻 PROGRAM:
~~~
def read_matrix(n):
    matrix=[[0]*n for row in range(n)]
    for i in range(n):
        lines=list(map(int,input().split()))
        for j in range(n):
            matrix[i][j]=lines[j]
    return matrix
def print_matrix(M):
    print("Matrix:")
    for i in range(len(M)):
        for j in range(len(M[0])):
            if(i>j or i==j):
                print(M[i][j],end=" ")
            else:
                print(0,end=" ")
        print()
~~~

## OUTPUT:
<img width="538" height="332" alt="image" src="https://github.com/user-attachments/assets/2b5943ae-db09-47d5-8d86-af6f3db8a962" />


## RESULT:
Thus the output is verified.
