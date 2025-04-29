# Azahar83-LabPerformance14-DCLP3
Problem:
Given a target integer T and a fixed list length k, evolve a list of k numbers (0–9) sum of the first two numbers equals the target T.
Case#1Input:
T = 7
k = 3
Case#1Output:
4 3 0
Case#2Input:
T = 10
k = 3

Given:target integer T, fixed list length k
Goal:Evolve a list of k digits (0–9) such that the sum of the first two elements equals the target T

The algorithm follows a simple evolutionary process:
Initialize a random list K of k digits from 0 to 9.
Evaluate the fitness: the closer the sum of K[0] + K[1] to T, the better.
Mutate a random element in the list.
Accept the mutation only if it improves or maintains the current fitness.
Repeat until the sum of the first two digits equals T.
