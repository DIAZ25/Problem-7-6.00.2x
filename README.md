# quiz Problem-7-6.00.2x 
Problem 7
0/20 points (graded)
Write a function that meets the specification below:

def solveit(test):
    """ test, a function that takes an int parameter and returns a Boolean
        Assumes there exists an int, x, such that test(x) is True
        Returns an int, x, with the smallest absolute value such that test(x) is True 
        In case of ties, return any one of them. 
    """
    # IMPLEMENT THIS FUNCTION

#### This test case prints 49 ####
def f(x):
    return (x+15)**0.5 + x**0.5 == 15
print(solveit(f))

#### This test case prints 0 ####
def f(x):
    return x == 0
print(solveit(f))

My code is:
def solveit(f):
  i=0
  while f(i)==False:
     i+=1
  return i
  
for solveit function. This code is crossing the time constraints. Hence how can i reduce the time of the following code. Basically, pls help me make this code more efficient.
