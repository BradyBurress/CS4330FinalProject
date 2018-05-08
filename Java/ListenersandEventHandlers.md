#Listeners and Event Handlers


Action Listeners are placed on an object which fires an event when a condition is met.


In this example the condition is the button being pressed.


The ActionEvent then runs a block of code


```
public class ButtonThing implements ActionListener {

  button.addActionListener(this);

  public void actionPerformed(ActionEvent e){
    System.out.println("Button was pressed");
  }
}
```

