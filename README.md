# Fibonacci-Sequence-Generator
Prints the Fibonacci sequence up to n terms
n = int(input("Number of terms: "))
a, b = 0, 1
for _ in range(n):
    print(a, end=" ")
    a, b = b, a + b
