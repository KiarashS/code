## Dynamic function parameters using annotations 
Originally published: 2012-02-22 22:29:11 
Last updated: 2012-02-22 22:31:02 
Author: pavel  
 
Python default values for keyword arguments are evaluated only once and not on every function call. For example following function will not work as user may expect: