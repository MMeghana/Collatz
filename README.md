# Collatz

Starting with any positive integer n, 
Collatz sequence is defined to n as the numbers formed by operations like:

if n is even , then n = n/2.   ->  6/2 = 3   10/2 = 5 -> 16/2 = 8 -> 8/2 = 4 -> 4/2 = 2 -> 2/2 = 1
if n is odd, then n = 3*n+1. -> 3*3+1 = 10 -> 3*5 + 1 = 16
Repeat above steps , until it becomes 1.

Input: 3
output:  3,10,5, 16, 8, 4,2,1

Input : 6
output : 6, 3,10,5, 16, 8, 4,2,1
