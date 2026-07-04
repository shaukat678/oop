## Python OOP MCQs (31–60)

**Beginner Level • No Answers Included**

---

### 31. What is the output?

```python
class Laptop:
    def show(self):
        print("Laptop")

l = Laptop()
l.show()
```

A) Laptop

B) show

C) Error

D) None

---

### 32. Which of the following is used to access an object's method?

A)

```python
object->method()
```

B)

```python
object.method()
```

C)

```python
method.object()
```

D)

```python
method(object)
```

---

### 33. What is the output?

```python
class Student:
    def __init__(self, name):
        self.name = name

s = Student("Sara")
print(s.name)
```

A) Student

B) Sara

C) name

D) Error

---

### 34. Which keyword is used inside a method to refer to the current object?

A) this

B) current

C) self

D) object

---

### 35. What is the output?

```python
class Book:
    def __init__(self):
        print("Book Created")

b = Book()
```

A) Book

B) Book Created

C) None

D) Error

---

### 36. Which statement is correct?

A) A class is created from an object.

B) An object is created from a class.

C) Methods cannot exist inside classes.

D) Objects cannot store data.

---

### 37. What is the output?

```python
class A:
    pass

a = A()

print(type(a).__name__)
```

A) object

B) A

C) class

D) Error

---

### 38. Which method initializes an object?

A) **start**()

B) **init**()

C) **create**()

D) **main**()

---

### 39. What is the output?

```python
class Student:
    def display(self):
        print("Hello")

Student().display()
```

A) Hello

B) Student

C) display

D) Error

---

### 40. What does an object contain?

A) Data and methods

B) Only variables

C) Only functions

D) Only loops

---

## Encapsulation

### 41. Which variable is intended to be private?

A)

```python
age
```

B)

```python
_age
```

C)

```python
__age
```

D)

```python
___age
```

---

### 42. What is the output?

```python
class Test:
    def __init__(self):
        self.value = 50

t = Test()
print(t.value)
```

A) value

B) 50

C) Test

D) Error

---

### 43. Which concept combines data and methods into one unit?

A) Inheritance

B) Encapsulation

C) Polymorphism

D) Abstraction

---

### 44. Why are private variables used?

A) To improve printing

B) To hide data from direct access

C) To increase loop speed

D) To create objects

---

### 45. Which of the following follows Python's naming convention for a protected attribute?

A)

```python
_marks
```

B)

```python
__marks__
```

C)

```python
marks
```

D)

```python
###marks
```

---

## Inheritance

### 46. What is the output?

```python
class Animal:
    def eat(self):
        print("Eating")

class Cat(Animal):
    pass

c = Cat()
c.eat()
```

A) Animal

B) Eating

C) Cat

D) Error

---

### 47. Which class inherits another class?

A) Parent class

B) Base class

C) Child class

D) Main class

---

### 48. Which type of inheritance is shown?

```python
class A:
    pass

class B(A):
    pass
```

A) Multiple

B) Single

C) Hierarchical

D) Hybrid

---

### 49. What is inherited from the parent class?

A) Methods and attributes

B) Only constructors

C) Only variables

D) Nothing

---

### 50. Which keyword is commonly used to access parent class methods?

A) parent

B) base

C) super()

D) self()

---

## Polymorphism

### 51. What is the output?

```python
class Bird:
    def fly(self):
        print("Flying")

class Eagle(Bird):
    def fly(self):
        print("Eagle Flying")

e = Eagle()
e.fly()
```

A) Flying

B) Eagle Flying

C) Bird

D) Error

---

### 52. The process of redefining a parent class method in a child class is called

A) Overloading

B) Overriding

C) Encapsulation

D) Initialization

---

### 53. Which OOP pillar allows different classes to use the same method name?

A) Abstraction

B) Polymorphism

C) Constructor

D) Object Creation

---

### 54. What is the output?

```python
class Shape:
    def area(self):
        print("Shape Area")

class Circle(Shape):
    def area(self):
        print("Circle Area")

c = Circle()
c.area()
```

A) Shape Area

B) Circle Area

C) Both

D) Error

---

### 55. Which concept increases flexibility by allowing different implementations?

A) Inheritance

B) Polymorphism

C) Encapsulation

D) Constructor

---

## Abstraction

### 56. Which module is imported to create abstract classes?

A) math

B) os

C) abc

D) sys

---

### 57. Which decorator is used with abstract methods?

A)

```python
@staticmethod
```

B)

```python
@property
```

C)

```python
@abstractmethod
```

D)

```python
@classmethod
```

---

### 58. Which statement about abstract classes is correct?

A) They can always be instantiated.

B) They may contain abstract methods.

C) They cannot contain normal methods.

D) They cannot have constructors.

---

## Mixed Concepts

### 59. What is the output?

```python
class Parent:
    def __init__(self):
        print("Parent")

class Child(Parent):
    pass

c = Child()
```

A) Parent

B) Child

C) Parent Child

D) Error

---

### 60. Which OOP pillar focuses on hiding implementation details from the user?

A) Inheritance

B) Polymorphism

C) Abstraction

D) Looping
