There are two ways to do recursion:
The first approach uses a while loop. While the pile isn’t empty, grab a box and look through it:
![[Pasted image 20250120094427.png]]
That’s why every recursive function has two parts: the base
case, and the recursive case. The recursive case is when the function calls
itself. The base case is when the function doesn’t call itself again … so it
doesn’t go into an infinite loop.