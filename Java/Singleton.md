#Singleton


Singleton ensures that there is only one instantiated object of a certain class to ensure that there are not unintended duplicates.


Singleton also provides a single global way to access the object.


```
Singleton x = Singleton.getInstance();

Singleton y = Singleton.getInstance();

Singleton z = Singleton.getInstance();
```


The same instance of singleton is referenced through the variables x, y, and z.