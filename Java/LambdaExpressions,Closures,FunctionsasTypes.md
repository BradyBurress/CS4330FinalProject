# Lambda Expressions, Closures, Functions as Types


A lambda is a function which can be created without being part of a class


```
Runnable r1 = () -> System.out.println("Lambda Example");
```


A closure is a block of code that can be referenced. This can be done with anonymous inner classes.


```
Runnable r = new Runnable()
{

};
```


Java does not support functions as types.
