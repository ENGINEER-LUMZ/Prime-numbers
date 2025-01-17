"# Prime-numbers" 

Creating a Function to Check if a Number Is Prime

my first task was to create a Python function, is_prime(n), that determines whether a given number n is prime. This function should return either True or False.

i initially approached this problem by considering the special cases. So, at the top of the function, I wrote an if statement that checks whether n is 0 or 1. If it is, the function should return False because these are not considered prime numbers.

Next, I iterated through each number between 2 and square root of n. If n is divisible by any number greater than sqrt(n), 
its counterpart in the product would be a number smaller than sqrt(n), thus, we would have already checked it. If any of these numbers are found to be divisors of n, we can claim that n is not prime. Consequently, return False at this point. Since there can be only one return per function, the function will stop immediately once it encounters this return.

Finally, if the function did not stop and went through the whole loop uninterrupted, n was not divisible by a number between 2 and sqrt(n). Therefore, n is a prime number; you can return a True value.

Creating a Function to Count Prime Numbers in a Range
I Initialized a variable 'count' and set its initial value to 0;

Next Set up a loop that goes through every number in the given range;

For each number, i applied the function 'is_prime()' to check if it’s a prime;

If the number is prime, increase the value of count by 1;

After the loop, it prints out the value of count.
