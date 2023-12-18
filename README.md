# factors-of-a-number
<br># Python Program to find the factors of a number


<br># This function computes the factor of the argument passed
<br>def print_factors(x):
 <br> print("The factors of",x,"are:")
  <br> for i in range(1, x + 1):
   <br>    if x % i == 0:
    <br>       print(i)

<br>num = 320

<br>print_factors(num)
