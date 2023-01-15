# Product-of-consecutive-Fib-numbers
The Fibonacci numbers are the numbers in the following integer sequence (Fn):

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, ...

such as

F(n) = F(n-1) + F(n-2) with F(0) = 0 and F(1) = 1.

Given a number, say prod (for product), we search two Fibonacci numbers F(n) and F(n+1) verifying

F(n) * F(n+1) = prod.

The function takes an integer (prod) and returns an array: *[F(n), F(n+1), True]* if **F(n) * F(n+1) = prod**.

If you don't find two consecutive F(n) verifying F(n) * F(n+1) = prod, you will return: *[F(n), F(n+1), False]* 
F(n) being the smallest one such as **F(n) * F(n+1) > prod**.

Some Examples of Return:

1. productFib(714):  
return [21, 34, True],   
since F(8) = 21, F(9) = 34 and 714 = 21 * 34

2. productFib(800)  
return [34, 55, False],  
since F(8) = 21, F(9) = 34, F(10) = 55 and 21 * 34 < 800 < 34 * 55

The exercise is on [Codewars](https://www.codewars.com/kata/5541f58a944b85ce6d00006a)
