# OS-SEM2-(2021-2022)


Assignment-1: 
Problem Statement-
Write a C program to solve an NxN sudoku puzzle by brute force. The program should be compatible on an Ubuntu machine running 18.04 or 20.04
  - 0<N<=36, N is a perfect square. The value of N will be supplied as a command line argument. 
  - The grid to be solved will be supplied as a text file as a command line argument. Empty cells in the grid have 0. Numbers greater than 9 will be represented by the number itself.
  - So, your program should run as : ./sudoku.out N input.txt
  - The program should print the solved grid on the standard output in a tab separated format, similar to the input.
  - Your program should take advantage of parallelism offered by the Linux fork(), IPC and pthread libraries. It is compulsory to use either fork() or pthread or both. Your program should spawn multiple (as many as required) child processes and/or threads to divide and conquer the problem in parallel.
