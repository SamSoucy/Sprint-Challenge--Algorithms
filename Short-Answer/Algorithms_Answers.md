Add your answers to the Algorithms exercises here.

## Exercise I

a) O(n)

b) O(n) * O(n) * O(n) = O(n^3) 

c) O(n)  this is a recursive function.

## Exercise II

Half the number of floors until the correct floor is found. Divide the floors by 2 and start on that floor. Drop the egg off that floor. If the egg breaks that would become the top floor and then you know the correct floor is below you. If it does not break, then that would become the bottom floor and the correct floor is above you. Continue the process of dividing the floors by 2, dropping the egg and moving in the right direction until the correct floor is found. 

O(n)