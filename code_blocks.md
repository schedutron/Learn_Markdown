Here's my code:

    thing = "World"
    print("Hello, %s!" % thing)
Here's the C version:
```c
#include<stdio.h>
void main()
{
  char thing[6];
  strcpy(thing, "World");
  printf("Hello, %s!\n", thing);
}
```
What about shell?
```
echo "hello"
```
Hey did you try `print("Hello, World!")`?

For Python 2.x:
```diff
thing = "World"
- print("Hello, %s!", % thing)
+ print "Hello, " + thing + "!"
```
