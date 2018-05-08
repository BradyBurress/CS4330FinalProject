# Errors and Exception Handling


Exception classes inherit from the class Throwable. 


Children of Throwable must have a stack trace, message, and optional clause


```
throw Exception("Error")

try{

  println("Try")

} catch(e: Exception) {

  println("Catch")

} finally{

  println("Finally")

}
```


