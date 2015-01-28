#Data Types

##Primitives
* Primitive data types in Java are built-in values that carry out basic, universal functionalities, such as: counting, measuring, deciding, and communicating. 
* There are eight primitive data types in Java. 
* They are: byte, short, int, long, float, double, boolean, and char.
* Primitives are the building blocks for everything else in Java-- you get them 'for free' with the language, and you can't break them down into any components. 

##Classes
* A class is a programmer-defined data type. 
* A class has:
      * Fields
        * These are values
      * Methods
        * These describe behavior
* A quick example: 
```
public class Car
{
  private String modelName;
  private String color;
  private int year;
  private int price;

  /**
   * This is the constructor, a special method which instantiates a new car. 
   * It initializes the instance variables. 
   */
  public Car(String modelName, String color, int year, int price)
  {
    this.modelName = modelName;
    this.color = color;
    this.year = year;
    this.price = price;
  }
  
  /**
   * A mutator method. Changes a car's state.
   */
  public void rePaintCar(String newColor)
  {
    this.color = newColor;
  }
  
 /**
  * An accessor method. Returns information about the car's state. 
  */
  public int getPrice()
  {
    return price;
  }
}
```    


##Objects

[In progress]
