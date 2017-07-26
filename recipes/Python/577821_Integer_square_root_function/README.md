## Integer square root function 
Originally published: 2011-08-04 05:29:16 
Last updated: 2011-08-04 05:29:16 
Author: Steven D'Aprano 
 
The *integer square root* function, or isqrt, is equivalent to floor(sqrt(x)) for non-negative x. For small x, the most convenient way to calculate isqrt is by calling int(x**0.5) or int(math.sqrt(x)), but if x is a large enough integer, the sqrt calculation overflows.