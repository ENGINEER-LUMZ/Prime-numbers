"# Prime-numbers" 

my first task was to create a Python function, is_prime(n), that determines whether a given number n is prime. This function should return either True or False.

i initially approached this problem by considering the special cases. So, at the top of the function, I wrote an if statement that checks whether n is 0 or 1. If it is, the function should return False because these are not considered prime numbers.

Next, I iterated through each number between 2 and n - 1. Within this loop, assess each number's divisibility with n. If any of these numbers are found to be divisors of n, we can claim that n is not prime. Consequently, return False at this point. Since there can be only one return per function, the function will stop immediately once it encounters this return.

Finally, if the function did not stop and went through the whole loop uninterrupted, n was not divisible by a number between 2 and n - 1. Therefore, n is a prime number; you can return a True value.
