# Print-Number-Triangle-Pattern-with-Spaces

You are given a positive integer N.

Your task is to print a number triangle pattern where:

The pattern contains N rows.
The number printed in each row is equal to the row number.
Each number in a row is separated by a single space.
The count of numbers in a row is equal to the row number.
Input
A single integer N.
Output
Print the number triangle pattern exactly as shown.
Constraints
1 ≤ N ≤ 100

N = int(input())

for i in range(1, N + 1):
    for j in range(1, i + 1):
        print(i, end="")
        if j < i:
            print(" ", end="")
    print()
