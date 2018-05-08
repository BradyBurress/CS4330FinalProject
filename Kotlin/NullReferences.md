#Null References


Kotlin has a null value although by default references can not be null. 


To allow a reference to be null, you must use the ? operator to make it an optional. 


```
var a: String? = "name"
```


Optionals handle the majority of null exceptions, although there are other ways to ensure that a reference is not null.


Checking for null directly:


```
if(a != null)
```


Safe call:


```
a?.length
```


Elvis Operator:


```
val b = a?.length ?: -1
```


!! Operator


```
val b = a!!.length
```


