# description: 
 The operands to the comma operator are evaluated from left to right.  The value of the left hand expression is discarded.  The type and value of the result are the type type and value of the right hand operand.  Note: assignment takes precedence over the comma operator, so in this case x=1 is evaluated first; than x, 2, 3
```C++ runnable
#include <iostream>

int main(int argc, char** argv)
{
  int x;

  x = 1, 2, 3;

  std::cout << x << std::endl;

  return 0;
}
