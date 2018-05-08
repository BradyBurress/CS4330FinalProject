# Multithreading


Multithreading in Kotlin is handled by coroutines. Coroutines can run in parallel and are very cheap compared to full threads.


The 'launch' function is used to start a coroutine. 


```
launch {
  ...
}
```


Coroutines can be paused by the delay() function which works like Thread.sleep()





