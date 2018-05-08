# Listeners and Event Handlers


Lambda Expressions can be used to add an Event Listener to an object.


```
fun setOnClickListener(listener: (View) -> Unit)


button.setOnClickListener({ view -> doSomething() })
```


This adds the listener and handles the event firing.



