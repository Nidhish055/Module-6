
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.

---

### ALGORITHM

1. Begin the program.
2. Define a class named `Student`.
3. Inside the class, create a constructor (`__init__`) that accepts `name` and `age` as parameters.
4. Declare `name` and `age` as private instance variables using double underscores (`__name`, `__age`).
5. Define `get_name()` and `get_age()` methods to return the private variables.
6. Define `set_name(name)` and `set_age(age)` methods to update the private variables.
7. Create an instance of the `Student` class and print the values using the getter methods.
8. Update the values using the setter methods and print the updated values.
9. End the program.

---

### PROGRAM

```python

# Name : Nidhish B
# Reg no. : 212223050032

class Student:
    def __init__(self, name, age):
        # private member
        self.__name = name
        self.__age = age
    
    def get_name(self):
        return self.__name
        
    def set_name(self,name):
        self.name=name
        
    def get_age(self):
        return self.__age
        
    def set_age(self,name):
        self.age=age

stud = Student('Jessa', 14)
print('Name:',stud.get_name(), stud.get_age())

stud=Student("Jessa",16)
print('Name:', stud.get_name(), stud.get_age())

```

### OUTPUT

![image](https://github.com/user-attachments/assets/e847d32b-2e94-4007-95fe-1f16fc1b4eaf)


### RESULT
Thus,a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable are verified.


