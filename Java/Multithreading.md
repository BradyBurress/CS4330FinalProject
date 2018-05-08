#Multithreading


In java there are two ways to perform multithreading


The Thread Class

The thread class can be extended by a class to give it the functionality of a thread.


```
public class Example extends Thread{

}
```


The Runnable Interface


As an interface it can be implemented by any class.


```
public class Example implements runnable {
  public void run {
    System.out.println("This is a thread")
  }
}
```