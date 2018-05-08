#Inheritance and Extension


In Kotlin a superclass must contain the keyword 'open' because they are final by default. 


```
open class Parent{

}

class Child: Parent{

}
```


Caalling superclass methods, constructors, and fields is done with the 'super' keyword.