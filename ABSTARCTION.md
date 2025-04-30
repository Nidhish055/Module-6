## Abstraction

---

### AIM  
To write a Python program to define the abstract base class named `Polygon` and also define the abstract method. This base class is inherited by various subclasses. Implement the abstract method in each subclass. Create objects of the subclasses and invoke the `sides()` method.

---

### ALGORITHM

1. **Start the Program.**
2. **Import the ABC class** from the `abc` module to implement abstraction.
3. **Define the abstract base class Polygon**:
   - Inherit from `ABC` (Abstract Base Class).
   - Define an abstract method `sides()` with no implementation.
4. **Define the Triangle class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Triangle has 3 sides"`.
5. **Define the Pentagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Pentagon has 5 sides"`.
6. **Define the Hexagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Hexagon has 6 sides"`.
7. **Define the Square class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"I have 4 sides"`.
8. **Create an object `t` of the Triangle class** and call the `sides()` method to print the number of sides.
9. **Create an object `s` of the Square class** and call the `sides()` method to print the number of sides.
10. **Create an object `p` of the Pentagon class** and call the `sides()` method to print the number of sides.
11. **Create an object `k` of the Hexagon class** and call the `sides()` method to print the number of sides.
12. **End the Program.**

---

### PROGRAM

```python

# Name : Nidhish B
# Reg No : 212223050032

from abc import ABC,abstractmethod
  
class Polygon(ABC):
    @abstractmethod
    def sides(self):
        pass  
  
class Triangle(Polygon):   
  
   def sides(self):   
      print("Triangle has 3 sides") 
      
class square(Polygon): 
    def sides(self):
        print("I have 4 sides")
  
class Pentagon(Polygon):
    def sides(self):
        print("Pentagon has 5 sides")
    
class Hexagon(Polygon):
    def sides(self):
        print("Hexagon has 6 sides")
        
t = Triangle()
s = square()   
p = Pentagon()
k = Hexagon()
t.sides()
s.sides()
p.sides()
k.sides()



```

### OUTPUT

![image](https://github.com/user-attachments/assets/472c8843-d805-49df-8991-32f35ef5e87d)

### RESULT

Thus the abstraction program has been successfully executed.
