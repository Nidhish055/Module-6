
## Operator Overloading

---

### AIM  

To write a Python program to perform addition of two complex numbers using the binary '+' operator overloading.

---

### ALGORITHM

 1. Start the program.
 2. Define a class named 'complex' with a constructor (__init__) that accepts two parameters: a and b.
 3. Initialize instance variables self.a and self.b with the given values.
 4. Define the __add__ method to overload the '+' operator.
 5. Inside the __add__ method, subtract other.a from self.a and other.b from self.b, and return the result as a tuple.
 6. Create two objects of the class with given values (e.g., Ob1 = complex(1, 2), Ob2 = complex(2, 3)).
 7. Use the '+' operator to add the two objects (Ob1 + Ob2), which will call the __add__ method.
 8. Store the result in a new object (Ob3) and print the result.
 9. End the program.

---

### PROGRAM

```python

# Name : Nidhish B
# Reg no. 212223050032

class complex:
	def __init__(self, a, b):
		self.a = a
		self.b = b

	def __sub__(self, other):
		return self.a - other.a, self.b - other.b

Ob1 = complex(1, 2)
Ob2 = complex(2, 3)
Ob3 = Ob1 - Ob2
print(Ob3)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/7e11e656-45f5-49b7-b5df-6cd49c11e168)

### RESULT

Thus the python program to perform division of two complex numbers using the binary '+' operator overloading is verified and successfully executed.

