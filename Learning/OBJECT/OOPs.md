### Basic Questions

1. **Define a Class**: Create a class named `Car` with attributes `make`, `model`, and `year`.
    
2. **Create an Object**: Instantiate an object of the `Car` class and print its attributes.
    
3. **Constructor**: Modify the `Car` class to include a constructor that initializes the attributes.
    
4. **Method Creation**: Add a method `display_info()` to the `Car` class that prints the car's details.
    
5. **Encapsulation**: Create a class `BankAccount` with private attributes `account_number` and `balance`. Add methods to deposit and withdraw money.
    
6. **Getters and Setters**: Implement getter and setter methods for the `balance` attribute in the `BankAccount` class.
    
7. **Inheritance**: Create a class `ElectricCar` that inherits from the `Car` class and adds an attribute `battery_size`.
    
8. **Method Overriding**: Override the `display_info()` method in the `ElectricCar` class to include battery size.
    
9. **Multiple Inheritance**: Create two classes `Engine` and `Wheels`, and create a class `Vehicle` that inherits from both.
    
10. **Polymorphism**: Create a method `start()` in the `Car` class and override it in the `ElectricCar` class to demonstrate polymorphism.
    

### Intermediate Questions

1. **Abstract Class**: Create an abstract class `Shape` with an abstract method `area()`. Implement this in subclasses `Circle` and `Rectangle`.
    
12. **Interface**: Define an interface `Drivable` with a method `drive()`. Implement this interface in the `Car` class.
    
13. **Composition**: Create a class `Person` that has a `Car` object as an attribute.
    
14. **Static Method**: Add a static method to the `Car` class that returns the number of `Car` instances created.
    
15. **Class Method**: Create a class method in the `BankAccount` class that returns the total number of accounts created.
    
16. **Class Variables**: Use class variables to keep track of the number of instances of the `Car` class.
    
17. **Destructor**: Implement a destructor in the `BankAccount` class that prints a message when an account is deleted.
    
18. **Copy Constructor**: Create a copy constructor for the `Car` class that allows you to create a new `Car` object from an existing one.
    
19. **Operator Overloading**: Overload the `+` operator in a class `Vector` to add two vectors.
    
20. **Chaining Constructors**: Use constructor chaining in the `Car` class to initialize default values.
    

### Advanced Questions

1. **Exception Handling**: Modify the `BankAccount` class to raise an exception if a withdrawal exceeds the balance.
    
22. **Private Methods**: Create a private method in the `Car` class that calculates the age of the car.
    
23. **Class Inheritance**: Create a base class `Animal` and derived classes `Dog` and `Cat`. Implement a method `speak()` in each.
    
24. **Method Chaining**: Implement method chaining in the `BankAccount` class for deposit and withdrawal methods.
    
25. **Dynamic Method Resolution**: Demonstrate dynamic method resolution using a base class reference pointing to a derived class object.
    
26. **Factory Method**: Implement a factory method in a class `ShapeFactory` that creates different shapes based on input.
    
27. **Singleton Pattern**: Implement a singleton pattern in a class `Logger` that ensures only one instance exists.
    
28. **Decorator Pattern**: Create a simple decorator pattern to add functionality to a `Coffee` class.
    
29. **Observer Pattern**: Implement a simple observer pattern where a `WeatherStation` notifies `Display` objects of changes.
    
30. **State Pattern**: Create a class `TrafficLight` that changes its state between `Red`, `Yellow`, and `Green`.
    

### Practical Applications

1. **Library System**: Create a class `Book` with attributes like `title`, `author`, and `ISBN`. Implement methods to check in and check out the book.
    
32. **Student Management**: Create a class `Student` with attributes `name`, `roll_number`, and `grades`. Implement a method to calculate the average grade.
    
33. **Shopping Cart**: Create a class `ShoppingCart` that can add, remove, and display items.
    
34. **Employee Management**: Create a class `Employee` with attributes `name`, `id`, and `salary`. Implement a method to give a raise.
    
35. **Game Character**: Create a class `Character` with attributes `name`, `health`, and `attack_power`.