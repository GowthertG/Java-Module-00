### Find if The Number is Prime or Not

The algorithm suggests that, with the exception of 2 and 3, all prime numbers can be written in the form of 6k ± 1, where k is an integer. This means that if you want to check if a number n is prime, you don't need to check all numbers. Instead:

1. First, check if n is divisible by 2 or 3. If it is, it's not prime.
2. If not, check numbers in the form 6k + 1 and 6k - 1, for values of k such that 6k + 1 ≤ n or 6k - 1 ≤ n.


