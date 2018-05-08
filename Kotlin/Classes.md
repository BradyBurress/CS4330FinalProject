# Classes


#Defining


Classes are defined by using the keyword class followed by a name and a set of curly braces


```
class Student(val major: String) {

}
```


---


#Creating New Instances


To create an instance of a class you simply call the constructor


```
var csStudent = Student("Computer Science")
```

---


#Initializing


Kotlin has two types of constructors 


The primary constructor is part of the class declaration. In the student class, it will automatically know to accept a String and place it in the field: major.


The primary constructor can also be directly manipulated using an init block:


```
init{

}
```


A secondary constructor can be created using the constructor keyword:


```
constructor(graduationYear: String){
  
}
```


---


#Deinitializing


Deinitializing is not required in Kotlin
